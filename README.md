# Prueba – Animaciones en CSS

Este proyecto corresponde a la Prueba del módulo **CSS Avanzado** de Desafío Latam.
El objetivo fue construir una página web temática que cumpla los **5 requerimientos oficiales**: menú lateral con logo, adaptación con media queries, galería animada, footer con contacto/redes y una apariencia visual coherente con la marca.

---

## 🚀 Live Project

Publicación en GitHub Pages (opcional):
👉 **Actualiza este enlace cuando publiques**: [https://fanuneza.github.io/fanuneza-adl-animaciones-con-css/](https://fanuneza.github.io/fanuneza-adl-animaciones-con-css/)


---

## 📂 Estructura del proyecto

* `index.html` → Maquetado principal (Hero, Galería, Cuidados, Footer). 
* `assets/css/style.css` → Estilos mobile-first, tokens de diseño, animaciones y media queries. 
* `assets/img/` → Imágenes de la galería + logo. 

---

## 🧩 Requerimientos cumplidos

* **Menú lateral con logo (Grid/Flex)**, que en móviles pasa a la parte superior. Incluye branding “Mundo Suculenta” + tagline. 
* **Sitio responsive con media queries**: layout mobile-first; tablet y desktop ajustan columnas/espaciados. 
* **Sección principal = Galería** con **transición/transformación**: tarjetas con `transform: scale()` y **caption** con fade/slide al hover/focus.  
* **Footer** con contacto y enlaces a redes; maquetado con Grid y **adaptativo**.  
* **Apariencia visual coherente** (tema, paleta y tipografía) según la marca del sitio.   

---

## 🧱 Arquitectura & Layout

* **Mobile-first** con breakpoints en **768px** (tablet) y **1024px** (desktop). La galería evoluciona de 1→3 columnas. 
* En **desktop** el header funciona como **sidebar sticky** usando **CSS Grid** a nivel de `body`.  
* **Secciones:** Hero (H1 + CTA), Galería (12 tarjetas), Cuidados (3 tips), Footer (3 columnas).    

---

## 🎨 Diseño & Animaciones

* **Tokens de diseño** (colores, espaciado, radio, tipografías del sistema).
* **Hover consistente** en tarjetas: elevación + `scale(1.04)` y **caption** con `opacity`/`translateY`. 
* **Tipografías**: serif para títulos, sans-serif para cuerpo. **Hero** con tamaño fluido. 

---

## 🛠️ Tecnologías utilizadas

* **HTML5**
* **CSS3 (Grid, Flexbox, Media Queries, Transitions/Transforms)**

---

## 📜 Licencia

Proyecto educativo del programa **Desafío Latam**. Uso libre con fines de aprendizaje.