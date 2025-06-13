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

![Loggin](https://github.com/SamuelPerez098/Proyecto-m-vil-android/blob/main/WhatsApp%20Image%202025-06-13%20at%2011.00.54%20AM.jpeg?raw=true)

![Activity](https://github.com/SamuelPerez098/Proyecto-m-vil-android/blob/main/WhatsApp%20Image%202025-06-13%20at%2011.01.20%20AM.jpeg?raw=true)


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

![Ejercicio 2](https://github.com/SamuelPerez098/Proyecto-m-vil-android/blob/main/WhatsApp%20Image%202025-06-13%20at%2011.01.38%20AM.jpeg?raw=true)



##  Tecnologías utilizadas

- Kotlin
- Android SDK
- AndroidX AppCompat
- XML para diseño de interfaces
