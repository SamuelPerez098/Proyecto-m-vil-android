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

### Logging
Esta es la actividad principal de la aplicación Android. Actúa como menú principal desde el cual el usuario puede acceder a cada uno de los 10 ejercicios disponibles.

- Aplica el diseño de pantalla completa utilizando enableEdgeToEdge() y ajusta los márgenes según las barras del sistema.

- Define 10 botones, cada uno para abrir una actividad específica (Ejercicio1Activity hasta Ejercicio10Activity).

- Usa setOnClickListener para lanzar cada actividad mediante un Intent.



Pantalla de inicio de sesión que valida:

- Que el correo tenga un formato válido.
- Que la contraseña coincida con `tap*2025`.

Si ambas condiciones se cumplen, se permite el acceso a la aplicación principal (`MainActivity`).

---

###  MainActivity

Pantalla principal con navegación a los distintos ejercicios mediante botones:

- Ejercicio 1 a Ejercicio 10

**Funcionalidades principales:**

- Aplica el diseño de pantalla completa con `enableEdgeToEdge()`.
- Ajusta márgenes según las barras del sistema con `WindowInsetsCompat`.
- Usa botones para iniciar actividades con `Intent`.

---

###  Ejercicio1Activity - Checkboxes

Permite al usuario seleccionar entre tres animales:

-  Perro
-  Gato
-  Ratón

Al presionar "Aceptar", se muestra un resumen de los animales seleccionados. Incluye un botón para regresar al menú principal.

---

###  Ejercicio2Activity - NumberPicker

Simula un selector numérico desde -10 a 10 en incrementos de 2.

**Funcionalidad:**

- Muestra el valor seleccionado dinámicamente en un `TextView`.
- Botón para volver al menú principal.

---

### 📝 Ejercicio3Activity - EditText y TextView

El usuario puede escribir texto en un campo y mostrarlo al pulsar un botón o en tiempo real.

---

###  Ejercicio4Activity - RadioButtons

Pantalla para seleccionar una opción entre varias (por ejemplo, género, color, etc.).

- Se muestra la opción seleccionada.
- Incluye botón para volver al menú.

---

###  Ejercicio5Activity - ListView

Muestra una lista de elementos (ej. nombres, cursos).

- Botón para cargar elementos.
- Botón para vaciar la lista.
- Muestra el ítem seleccionado.

---

### 🎚 Ejercicio6Activity - SeekBar

Control deslizante para seleccionar un valor.

- Muestra el valor en tiempo real.
- Útil para volumen, brillo, etc.

---

###  Ejercicio7Activity - Calculadora Básica

Permite realizar operaciones entre dos números:

- Suma
- Resta
- Multiplicación
- División

---

### 🗓 Ejercicio8Activity - DatePicker y TimePicker

Permite seleccionar una fecha y una hora.

- El resultado se muestra en un `TextView`.

---

###  Ejercicio9Activity - Conversor de divisas

Convierte un monto entre distintas monedas.

- Selección de moneda destino.
- Conversión con resultado mostrado.

---

###  Ejercicio10Activity - Cálculo de compra

Calcula el total de una compra aplicando:

- Subtotal
- IVA
- Descuento

Permite configurar el porcentaje de IVA y descuento.

---

![Loggin](https://private-user-images.githubusercontent.com/206933327/454961898-ca689937-b47a-40b8-8bf4-4b854fefea51.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDk4MzUxNDgsIm5iZiI6MTc0OTgzNDg0OCwicGF0aCI6Ii8yMDY5MzMzMjcvNDU0OTYxODk4LWNhNjg5OTM3LWI0N2EtNDBiOC04YmY0LTRiODU0ZmVmZWE1MS5qcGVnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI1MDYxMyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNTA2MTNUMTcxNDA4WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9ZTNmZjk0Y2JjNGVlZWZmMzU1ZTg3NWMyMDMxMzBiZGZmOWI5NGE2NGFjNmFhY2Q2YTJkZDM5OGE4MzBkYTBkOSZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.c5mjLTlkOsMHjwqTE1_4Re6-iFDYOuSFcH8l4qkMfQU)

![Activity](https://private-user-images.githubusercontent.com/206933327/454961900-94264170-f4b7-4470-8200-83110930873c.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDk4MzUxNDgsIm5iZiI6MTc0OTgzNDg0OCwicGF0aCI6Ii8yMDY5MzMzMjcvNDU0OTYxOTAwLTk0MjY0MTcwLWY0YjctNDQ3MC04MjAwLTgzMTEwOTMwODczYy5qcGVnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI1MDYxMyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNTA2MTNUMTcxNDA4WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9YzI2ZGM3MDI2NDcwYTE0ZTdmNDM0ZGZmYmVmZjVkNWFmMmNhNDVkZjBmMWQxY2RjZTFmZWY5NjE4MjM3NDE4OCZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.qIjEme1jpRKYm6elAGlDvQDuIDnPRq86a3Vyep3tLHE)


un ejemplo de la Estructura interna de uno de los ejeccicios seria : 

###  Ejercicio2Activity - NumberPicker

Esta actividad simula el uso de un `Spinner` numérico mediante un `NumberPicker`. Permite al usuario seleccionar un valor entero desde **-10 hasta 10** con incrementos de 2, mostrando dinámicamente el valor actual seleccionado.

####  Funcionalidades clave:

- Configura un `NumberPicker` con valores personalizados: `-10, -8, -6, ..., 10`.
- El valor seleccionado se refleja automáticamente en un `TextView` (`lblValor`).
- Incluye un botón **Volver al menú principal**, que redirige al usuario a `MainActivity`.

####  Componentes utilizados:
- `NumberPicker` (`spiValor`)
- `TextView` (`lblValor`)
- `Button` (`btnVolverMenu`)

####  Comportamiento:
1. El usuario selecciona un número del picker.
2. El número actual se muestra en tiempo real debajo.
3. Al presionar el botón de volver, se regresa al menú principal (`MainActivity`) y se limpia la pila de actividades para evitar navegación duplicada.

Esta actividad demuestra cómo personalizar un `NumberPicker` en Android y cómo manejar su evento `setOnValueChangedListener`.

![Ejercicio 2](https://private-user-images.githubusercontent.com/206933327/454961899-cc8733be-da50-40e6-95ad-e863282b9281.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDk4MzQ4ODAsIm5iZiI6MTc0OTgzNDU4MCwicGF0aCI6Ii8yMDY5MzMzMjcvNDU0OTYxODk5LWNjODczM2JlLWRhNTAtNDBlNi05NWFkLWU4NjMyODJiOTI4MS5qcGVnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI1MDYxMyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNTA2MTNUMTcwOTQwWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9YWUwZTk5ODA5Nzc4YjNkMTBjOTk5ZjVlZDMzNjNiOGZhYTA5NGQxNWI0OTJlNGRjYjE1ZmQxZDY2YWU5ZWY4YiZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.yOaQvZrs9Y6qCpeFJzFuiItdAl_fmEb5jL5jJ3kFBdc)



##  Tecnologías utilizadas

- Kotlin
- Android SDK
- AndroidX AppCompat
- XML para diseño de interfaces
