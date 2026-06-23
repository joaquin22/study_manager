# Study Manager

Aplicación Flutter para organizar tareas universitarias. El proyecto incluye una base visual simple, pantallas de autenticación y un tema centralizado para mantener consistencia en toda la app.

## Estructura de la app

La app está organizada por responsabilidad:

- `lib/main.dart`: punto de entrada de la aplicación. Define el tema y la pantalla de inicio.
- `lib/theme/app_theme.dart`: define los colores y estilos de la aplicación.
- `lib/screens/login_screen.dart`: pantalla de inicio de sesión con validación básica de correo y contraseña.
- `lib/screens/register_screen.dart`: pantalla de registro con validación de campos y confirmación de contraseña.


### Pantalla de Login

<p align="center">
	<img width="330" alt="image" src="https://github.com/user-attachments/assets/43bfa30e-9a99-4a0a-9514-5e66e3d0201d" />
</p>

### Pantalla de Registro
<p align="center">
	<img width="330" alt="image" src="https://github.com/user-attachments/assets/9fa1f067-d933-494a-993c-7ef849ae4958" />
</p>

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
