# La Forja Colaborativa ⚽

Proyecto web colaborativo para el TP8 de Funcionamiento de los Sistemas Digitales.

## Cómo colaborar (fork + pull request)

1. Hacé **Fork** de este repositorio.
2. Cloná tu fork y trabajá sobre esa copia.
3. En `index.html`:
   - Agregá tu nombre como un nuevo `<li>` dentro de `<ol class="roster-list">`, siguiendo el mismo formato que los existentes (`<span class="number">` + nombre).
   - Agregá una nueva `<article class="card">` dentro de `.card-grid`, con tu propia imagen en `img/`, un título y una descripción breve.
4. No modifiques la estructura general de la página ni el CSS existente (podés proponer mejoras de CSS justificadas en el PR).
5. Hacé commit y push a tu fork.
6. Abrí un **Pull Request** hacia este repositorio original, describiendo:
   - Qué modificaciones hiciste.
   - Qué tarjeta agregaste.
   - Qué archivos modificaste.
   - Si tuviste que ajustar algo para respetar la estructura original.

## Criterios visuales

- Las tarjetas usan imagen + `<h3>` + `<p>` dentro de `.card`.
- Las imágenes van en `img/` (SVG o PNG/JPG livianos).
- Mantené la paleta y tipografía definidas en `css/style.css`.
