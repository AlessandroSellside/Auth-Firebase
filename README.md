# Auth-Firebase

# Proyecto de autenticación con Firebase
Este proyecto muestra cómo implementar la autenticación con Firebase en una aplicación Flutter.

## Prerequisitos

Antes de comenzar, asegúrate de cumplir con los siguientes requisitos:

- Instalar Flutter
- Crear un proyecto Firebase
- Habilitar la autenticación en el proyecto Firebase

## Instrucciones

Sigue estos pasos para configurar y ejecutar el proyecto:

1. Clona el proyecto.
2. Abre el proyecto en Android Studio o Visual Studio Code.
3. Configura el proyecto Firebase:
   - Abre el archivo `firebase_options.dart`.
   - Agrega las claves de configuración de tu proyecto Firebase.
4. Ejecuta el proyecto:
   - Abre el archivo `pubspec.yaml`.
   - Ejecuta el comando `flutter pub get` para instalar las dependencias.
   - Ejecuta el comando `flutter run` para ejecutar el proyecto.

## Demostración

El proyecto consta de dos pantallas:

- Pantalla de inicio de sesión: Permite a los usuarios iniciar sesión con correo electrónico y contraseña o con Google.
- Pantalla principal: Muestra un mensaje de bienvenida al usuario autenticado.
