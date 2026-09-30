# Conversor de Unidades (Web App)

Una aplicación web sencilla, ligera e interactiva construida con **HTML5**, **CSS3** y **JavaScript** que permite realizar conversiones rápidas de unidades de longitud (Kilómetros a Metros y Metros a Centímetros).

---

## Características

* **Diseño Responsivo y Limpio:** Interfaz moderna centrada con tarjetas, esquinas redondeadas y una paleta de colores agradable.
* **Interactividad con JavaScript:** Validación en tiempo real al hacer clic en los botones de conversión o al modificar los valores de entrada.
* **Selector Dinámico:** Selector de tipo de conversión integrado con la lógica de los campos de entrada.

---

##  Tecnologías Utilizadas

* **HTML5:** Estructura de la página web.
* **CSS3:** Estilos visuales, distribución con Flexbox y diseño de componentes (`input`, `button`, `select`).
* **JavaScript (Vanilla):** Lógica de cálculo y manipulación del DOM.

---

##  Estructura del Código

El proyecto está contenido en un **único archivo** (`index.html`), lo que facilita su ejecución y despliegue sin dependencias complejas:

* **`<head>` / `<style>`:** Contiene los estilos CSS (centrado de página, contenedor principal, transiciones y efectos hover en botones).
* **`<body>`:** Define la estructura visual con un contenedor principal y dos secciones de conversión (`Km a M` y `M a Cm`).
* **`<script>`:** Contiene las funciones principales:
  * `convertirKm()`: Toma el valor de Kilómetros y lo transforma a Metros si la opción está seleccionada.
  * `convertirM()`: Toma el valor de Metros y lo transforma a Centímetros si la opción está seleccionada.

---

## 🖥️ Cómo usarlo localmente

1. Descarga o copia el código fuente en un archivo llamado `index.html`.
2. Haz doble clic en el archivo para abrirlo en cualquier navegador web moderno (Google Chrome, Firefox, Microsoft Edge, Safari).
3. Selecciona el tipo de conversión, ingresa un valor numérico y haz clic en **"convertir"**.

---



Creado con fines educativos y de práctica en desarrollo web frontend. ¡Si deseas mejorarlo o agregar más unidades de medida, siéntete libre de hacer un fork o pull request!
