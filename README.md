# vigiait-web

Web pública de **Vigía IT** — IT gestionado para pymes · https://vigiait.es

- Contenido publicable en `site/` (HTML estático, sin build).
- Cada push a `main` que toque `site/` se publica solo en GitHub Pages (`.github/workflows/pages.yml`).
- Dominio propio `vigiait.es` (DNS en STRATO: A al apex de GitHub Pages + CNAME `www`).
