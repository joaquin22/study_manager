# Study Manager

Aplicación Flutter para organizar tareas universitarias. El proyecto incluye una base visual simple, pantallas de autenticación y un tema centralizado para mantener consistencia en toda la app.

## Estructura de la app

La app está organizada por responsabilidad:

- `lib/main.dart`: punto de entrada de la aplicación. Configura `MaterialApp`, aplica el tema y abre la pantalla de login.
- `lib/screens/login_screen.dart`: pantalla de inicio de sesión con validación básica de correo y contraseña.
- `lib/screens/register_screen.dart`: pantalla de registro con validación de campos y confirmación de contraseña.
- `lib/theme/app_theme.dart`: define los colores, el tema visual y la configuración de componentes como botones, campos de texto y la AppBar.

## Flujo actual

1. La app inicia en `MyApp`.
2. Se carga el tema definido en `AppTheme.lightTheme`.
3. La pantalla inicial es `LoginScreen`.
4. Desde el login se puede navegar a `RegisterScreen`.
5. Ambas pantallas validan formularios antes de continuar.

## Capturas de pantalla

Aquí puedes agregar imágenes de la interfaz para documentar el estado visual de la app.

### Login

![Pantalla de login](assets/screenshots/login.png)

### Registro

![Pantalla de registro](assets/screenshots/register.png)

## Estructura de carpetas

```text
lib/
├── main.dart
├── screens/
│   ├── login_screen.dart
│   └── register_screen.dart
└── theme/
	└── app_theme.dart
```

## Estado actual

- La autenticación todavía no está conectada a un backend.
- En los métodos de login y registro hay marcadores `TODO` para integrar Supabase.
- El proyecto ya tiene una base lista para crecer con nuevas pantallas como tareas, calendario, perfil y ajustes.

## Requisitos

- Flutter SDK
- Un emulador o dispositivo físico para ejecutar la app

## Ejecutar la app

```bash
flutter pub get
flutter run
```
