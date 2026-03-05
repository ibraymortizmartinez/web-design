# 🌐 ConnectTech - Formulario de Contacto Moderno

Un formulario de contacto elegante, interactivo y completamente responsivo, diseñado desde cero utilizando **HTML5 semántico** y **CSS3 puro**. Este proyecto demuestra la capacidad de crear interfaces de usuario (UI) de alta calidad con un aspecto profesional, similar al de frameworks como Bootstrap, pero manteniendo un código ligero y personalizado sin dependencias externas pesadas.

---

## ✨ Características Principales

* 🎨 **Diseño Moderno "Bootstrap-like":** Estética limpia con bordes redondeados, paleta de colores cohesiva y tipografía nativa del sistema, lograda 100% con CSS puro.
* 🪟 **Efecto Glassmorphism:** Implementación de fondos translúcidos con `backdrop-filter: blur()` en el encabezado y pie de página para una integración elegante con la imagen de fondo.
* 📱 **100% Responsivo (Mobile-First adaptado):** Uso estratégico de *Media Queries* (`@media`) para asegurar que la navegación, el formulario y el footer se adapten perfectamente a pantallas de celulares, tablets y monitores de escritorio.
* ✨ **Micro-interacciones Avanzadas:** * Efectos `:focus-within` en los campos del formulario que iluminan el contenedor completo, mejorando la experiencia de usuario (UX).
    * Animaciones de levitación (`transform: translateY`) y sombras (`box-shadow`) dinámicas en botones y enlaces sociales al pasar el cursor (`:hover`).
* 🧩 **Logo Generado con CSS:** El logotipo "C" de ConnectTech está construido puramente con propiedades de bordes CSS, reduciendo las peticiones HTTP y el peso de la página.
* 🖼️ **Fondo Dinámico:** Combinación de una imagen de fondo con fijación (`background-attachment: fixed`), una capa semitransparente superpuesta y formas geométricas abstractas generadas con gradientes radiales y desenfoques.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica (`<header>`, `<main>`, `<section>`, `<footer>`) para mejor accesibilidad y SEO.
* **CSS3:** Flexbox para maquetación, variables de diseño, pseudo-clases, transiciones suaves y Media Queries.
* **FontAwesome (v6.4.0):** Implementación vía CDN para el uso de iconos vectoriales optimizados en los campos de entrada y botones de redes sociales.

---

## 📁 Estructura del Proyecto

```text
📦 connecttech-contacto
 ┣ 📂 assets
 ┃ ┣ 📂 css
 ┃ ┃ ┗ 📜 style.css       # Hoja de estilos principal (Diseño, UI y Responsive)
 ┃ ┗ 📂 img
 ┃ ┃ ┣ 🖼️ fondo2.jpg      # Imagen fotográfica de fondo
 ┃ ┃ ┗ 🖼️ solicitud.png   # Favicon del sitio
 ┗ 📜 index.html          # Estructura principal de la página y formulario