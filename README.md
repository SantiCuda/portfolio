# Portafolio Personal — Santiago Cuda

## Descripción del Proyecto

Este es el **Trabajo Práctico N°1 (PFO1)** de la materia. Se trata de una Landing Page de Portafolio Personal desarrollada íntegramente con **HTML5 y CSS3 puro**, sin frameworks de JavaScript. El sitio presenta mi perfil como desarrollador, mis proyectos reales publicados en GitHub, mis habilidades técnicas, un formulario de contacto y mis películas favoritas.

**URL del sitio publicado:** `[COMPLETAR CON TU URL DE GITHUB PAGES]`

---

## Checklist - Práctica Formativa Obligatoria 1

### Estructura del Proyecto:
- [x] Archivo "index.html" ubicado en la raíz.
- [x] Carpeta "css" que contenga el archivo "styles.css".
- [x] Carpeta "img" para recursos gráficos (foto de perfil e imágenes de proyectos).
- [x] Archivo "README.md" creado, que incluye una breve descripción del TP y este checklist.

### Repositorio y Publicación:
- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages.
- [ ] En el "README.md" se indica la URL de GitHub Pages. *(completar con tu URL)*

### Uso de Google Fonts:
- [x] Enlace a Google Fonts incluido en la sección "head" del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] **¿Por qué elegiste esa fuente?**
  Se eligieron **Rajdhani** para los títulos y **Outfit** para el cuerpo del texto. Rajdhani es una tipografía geométrica y bold que transmite un estilo técnico y moderno, ideal para un portafolio de desarrollo. Outfit aporta legibilidad y limpieza en los textos largos. La combinación crea un contraste visual efectivo entre impacto y lectura cómoda.

### HTML:
- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: `charset` y `viewport`.
- [x] Se ha definido un título descriptivo: *"Santiago Cuda — Developer"*.
- [x] Se han vinculado correctamente el archivo CSS (`css/styles.css`) y el enlace a Google Fonts.

#### Secciones obligatorias en "main":
- [x] Sección `#sobre-mi` — presentación personal con bio, foto y redes sociales.
- [x] Sección `#tarjetas` — 6 tarjetas de proyectos reales de GitHub con imagen, descripción y links.
- [x] Sección `#habilidades` — listado de tecnologías por categoría y tabla con niveles de experiencia.
- [x] Sección `#contacto` — formulario con campos Nombre, Apellido, Email y Teléfono, y botón submit.
- [x] Sección `#peliculas` — 3 películas favoritas con imagen, título, año y descripción.
- [x] Barra de navegación (`nav`) con 4 enlaces: Inicio, Sobre mí, Proyectos y Contacto.
- [x] Al menos 4 comentarios explicativos en el HTML con ideas de mejora a futuro.

### CSS:
- [x] Archivo "styles.css" con estilos personalizados.
- [x] Selectores por clases (`.card`, `.btn-acento`, `.hero-foto`, etc.) e IDs (`#sobre-mi`, `#tarjetas`, `#contacto`, `#peliculas`).
- [x] Tipografía importada desde Google Fonts aplicada en todos los elementos.

#### Layout y Organización:
- [x] Layout de la sección **tarjetas** con **CSS Grid** (`grid-template-columns: repeat(3, 1fr)`).
- [x] **Flexbox** en navegación, hero y componentes internos.
- [x] **¿Qué ventajas encontraste al utilizar Flexbox o Grid?**
  CSS Grid permitió crear la grilla de tarjetas de forma declarativa y responsiva, adaptándose a distintos anchos de pantalla. Flexbox fue ideal para alinear elementos dentro de cada componente (nav, hero, cards), simplificando el centrado vertical y horizontal. La combinación de ambos sistemas dio un layout robusto y fácil de mantener.

#### Estilización de Componentes:
- [x] Tablas personalizadas (`.tabla`, `.tabla th`, `.tabla td`, `.pill`).
- [x] Botones personalizados (`.btn-acento`, `.btn-ghost`, `.btn-full`).
- [x] Enlaces personalizados (`.nav-ico`, `.red`, `.card-repo-link`, `.footer-nav a`).
- [x] Formulario personalizado (`.form input`, `.form textarea` con focus states y box-shadow).
- [x] Dimensiones con unidades relativas: `rem` en tipografías, `%` en anchos, `vh` en el hero, `aspect-ratio` en imágenes.
- [x] **Animaciones y transiciones implementadas:**
  - `navFadeIn`: la barra de navegación aparece con fade + slide al cargar la página.
  - `navFadeInBottom`: en mobile, la barra inferior aparece desde abajo con fade.
  - Transición `hover` en tarjetas de proyectos (`translateY` + borde iluminado).
  - Transición `hover` en íconos de la nav lateral (escala con `scale(1.15)`).
  - Animación `reveal` con `IntersectionObserver` en tarjetas y secciones al hacer scroll.
  - Botón "volver al inicio" con fade-in al scrollear la página.

  **¿Por qué estas animaciones?** Las transiciones de hover guían la atención hacia los elementos interactivos. El fade-in del nav genera un efecto de carga elegante. El reveal progresivo al hacer scroll mejora la experiencia de lectura y da dinamismo al sitio sin distraer.

### Consideraciones Adicionales:
- [x] Diseño responsivo con breakpoints en 900px (tablet), 480px (mobile) y 380px (iPhone SE).
- [x] Accesibilidad: atributos `alt` en todas las imágenes, `aria-label` en íconos, uso semántico de `<nav>`, `<header>`, `<main>`, `<section>`, `<article>` y `<footer>`.
- [x] Comentarios en HTML describiendo decisiones de diseño y mejoras futuras.

---

## Estructura del Proyecto

```
/
├── index.html
├── README.md
├── cv_santiago_cuda.pdf
└── css/
    └── styles.css
```

## Tecnologías Utilizadas

- HTML5 semántico
- CSS3 (Flexbox, Grid, Custom Properties, Animaciones)
- Google Fonts (Rajdhani + Outfit)
- JavaScript vanilla (IntersectionObserver, eventos de scroll)
