# Fundación Patitas Felices

Proyecto web (HTML/CSS) para la **Fundación Patitas Felices**. Incluye páginas principales para inicio, adopción (galería) y contacto.

---

## Estructura del proyecto

- `index.html` : Página principal (módulo de misión, carrusel de rescates y navegación).
- `pages/`
  - `gallery.html` : Sección de adopción con tarjetas y perfiles ampliados.
  - `contact.html` : Formulario de contacto.
- `css/`
  - `style.css` : Estilos globales y responsive.
- `img/` : Imágenes usadas en el sitio.

---

## Cómo ejecutar / visualizar

1. Abre el archivo `index.html` en tu navegador.
2. Para navegar a las otras secciones:
   - Adopta: `pages/gallery.html`
   - Contacto: `pages/contact.html`

> Nota: al ser un proyecto estático, no requiere instalación ni un servidor (aunque puedes usar uno si lo deseas).

---

## Navegación

El sitio utiliza enlaces relativos:

- En `index.html`:
  - Inicio: `index.html`
  - Adopta: `pages/gallery.html`
  - Contacto: `pages/contact.html`

- En `pages/contact.html` y `pages/gallery.html`:
  - Inicio: `../index.html`

---

## Responsive (diseño adaptativo)

El archivo `css/style.css` incluye media queries para:

- **Mobile** (`max-width: 600px`): ajustes de carrusel, formulario y layout.
- **Tablet** (`601px - 1024px`): distribución en 2 columnas.
- **Desktop** (`min-width: 1025px`): catálogo centrado con tamaños fijos.

---

## Contacto

El formulario de contacto está en `pages/contact.html`. Actualmente su `action` es `#` (sin backend), por lo que el envío no procesa datos.

---

## Créditos

- Desarrollado por: **Omega Corp.**
- Año: 2026

