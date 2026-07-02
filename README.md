# Plantilla de sitio (diseño editorial)

Colección de demos que reutilizan un mismo diseño elegante (hero a pantalla completa, secciones editoriales, línea de tiempo y contacto) para distintos giros de negocio.

## Demos

- **Boda** — invitación de boda (versión original). → [`/`](https://miguelin777.github.io/boda-ananya-arjun/)
- **Salón / Hacienda de eventos** — "Hacienda Los Encinos", con animaciones e interactividad. → [`/salon/`](https://miguelin777.github.io/boda-ananya-arjun/salon/)
- Hotel / hospedaje — *(en construcción)*
- Destino turístico — *(en construcción)*
- Plantilla genérica reutilizable — *(en construcción)*

## Notas técnicas

- HTML estático + [Tailwind CSS (Play CDN)](https://tailwindcss.com) + fuentes Libre Caslon.
- Sin dependencias externas de JS: animación e interactividad en CSS + JS vanilla (IntersectionObserver + un solo scheduler `requestAnimationFrame`).
- Respeta `prefers-reduced-motion` y degrada de forma elegante si el JS no corre.
- Se sirve con GitHub Pages (`.nojekyll`).
