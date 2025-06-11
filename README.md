# MyApplication5 - Proyecto Android

Este es un proyecto Android desarrollado en Kotlin que contiene una serie de ejercicios prácticos con diferentes elementos de la interfaz gráfica y lógica básica. La aplicación comienza con una pantalla de login y luego permite acceder a distintos ejercicios.

##  Pantallas y funcionalidades

###  LoginActivity
Pantalla de inicio de sesión que valida:
- Que el correo tenga un formato válido.
- Que la contraseña coincida con `tap*2025`.

Si ambas condiciones se cumplen, se permite el acceso a la aplicación principal (`MainActivity`).

###  MainActivity
Pantalla principal con navegación a los distintos ejercicios mediante botones:
- Ejercicio 1 a Ejercicio 10

### Ejercicio1Activity - Checkboxes
Permite al usuario seleccionar entre tres animales (`Perro`, `Gato`, `Ratón`) mediante checkboxes. Al presionar "Aceptar", muestra un resumen de los animales seleccionados. También incluye un botón para volver al menú principal.

### Ejercicio2Activity - NumberPicker
Simula el comportamiento de un spinner numérico desde -10 a 10 con incrementos de 2:
- El valor seleccionado se muestra dinámicamente en un `TextView`.
- Incluye un botón para volver al menú principal.

<!-- Puedes seguir agregando secciones para Ejercicio3Activity a Ejercicio10Activity conforme los completes. -->

## Estructura del proyecto
com.example.myapplication5
-  LoginActivity.kt
- MainActivity.kt
- Ejercicio1Activity.kt
- Ejercicio2Activity.kt
-  Ejercicio3Activity.kt
- Ejercicio4Activity.kt
- Ejercicio5Activity.kt
-  Ejercicio6Activity.kt
-  Ejercicio7Activity.kt
-  Ejercicio8Activity.kt
-  Ejercicio9Activity.kt
- Ejercicio10Activity.kt



##  Tecnologías utilizadas

- Kotlin
- Android SDK
- AndroidX AppCompat
- XML para diseño de interfaces
