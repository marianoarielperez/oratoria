# Oratoria — Material de estudio

Material de estudio interactivo para la materia **Oratoria y técnicas de expresión** (Lic. en Periodismo, 2026). Cada módulo es una página autocontenida con:

- **Tarjetas de repaso** tipo Anki con filtros por tema
- **Quiz de autoevaluación** con corrección y explicaciones
- **Glosario buscable** de términos y autores

Todo funciona **offline**: cada HTML se abre con doble clic, sin instalar nada. También incluye modo oscuro (botón luna/sol).

## Contenido

| Página | Qué es |
|---|---|
| `index.html` | Portada con el selector de módulos |
| `modulo-1.html` | Módulo 1 — Principios de Oratoria (47 tarjetas · 28 preguntas · 49 términos) |

## Publicar en GitHub Pages (paso a paso)

1. Creá un repositorio público en GitHub (por ejemplo `oratoria-estudio`).
2. Subí **el contenido de esta carpeta** (`index.html`, `modulo-1.html`, `README.md`) a la raíz del repo. Desde la web de GitHub: *Add file → Upload files*, arrastrá los archivos y confirmá el commit.
3. En el repo: **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, carpeta `/ (root)`. Guardá.
4. En 1-2 minutos el sitio queda en `https://<tu-usuario>.github.io/oratoria-estudio/`.
5. Compartí ese link con tus compañeros. Cada vez que subas un cambio a `main`, Pages se actualiza solo.

> **Importante:** no subas los PDFs de la cátedra ni otro material con derechos de autor. Este repo solo lleva los HTML.

## Agregar un módulo nuevo

1. Copiá `modulo-1.html` como `modulo-2.html`.
2. Adentro del `<script>` reemplazá **solo** las constantes `MODULO`, `TARJETAS`, `QUIZ` y `GLOSARIO` con el contenido del módulo nuevo (y actualizá título, eyebrow y meta description).
3. En `index.html`, convertí la tarjeta "Módulo II — En preparación" en un link como el del Módulo I.

## Créditos

- Contenido basado en los módulos de la cátedra (Lic. Brenda López, UMAI).
- Íconos: [Lucide](https://lucide.dev) — licencia ISC, incrustados como SVG.
