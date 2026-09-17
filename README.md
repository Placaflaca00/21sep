# Jardín del 21 🌻

Una web de arte pixel para el 21 de septiembre — Día de la Primavera y del Amor.
Campo de girasoles y rosas amarillas dibujado con código, una abeja volando,
pétalos en el viento y música.

## Cómo verla

Abre `index.html` en el navegador. No necesita servidor ni instalar nada.

## Publicarla en GitHub Pages

1. Crea un repositorio en GitHub y sube estos archivos (`index.html`, `assets/`, `README.md`).
2. En el repo: **Settings → Pages → Source: Deploy from a branch → main / (root)**.
3. En un minuto queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

Para un dominio propio: cómpralo, apúntalo a GitHub Pages y ponlo en
**Settings → Pages → Custom domain**. GitHub crea un archivo `CNAME` en el repo.

## Personalizar

| Qué | Dónde |
|---|---|
| El mensaje y la firma | `index.html`, párrafo `class="note"` |
| El título y la fecha | `index.html`, dentro de `<header class="titleblock">` |
| La canción | reemplaza `assets/musica.mp3` (suena en bucle) |
| Dedicatoria por la URL | abre la página con `?para=Nombre` |
| Usuario de Instagram | `index.html`, el `<span id="iguser">` |
| Las burlas del botón | `index.html`, el array `BURLAS` |

## Detalles

- Todo el dibujo es código: no hay imágenes. Se pinta en un canvas de baja
  resolución y se escala con pixeles duros (`image-rendering: pixelated`).
- Tocando el campo se siembran flores nuevas. A las 21 aparece una sorpresa.
- El botón "Ver contraseña" es una broma: al intentar tocarlo, el recuadro
  entero salta a otro sitio. **No hay ninguna contraseña en el código**, solo
  puntitos — nada que se pueda leer viendo el código fuente de la página.
- La música arranca con el botón de la portada porque los navegadores no
  permiten reproducir audio sin un toque del usuario.
