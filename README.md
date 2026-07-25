# Color Scheme

**Color Scheme** es un generador inteligente de paletas de color. Crea combinaciones armoniosas a partir de un color base y previsualízalas en plantillas reales para ver cómo lucen antes de usarlas en tu proyecto.

## Características

- **Entrada por rueda de color** — Seleccioná el color base visualmente.
- **Extracción de color por imagen** — Subí una imagen y extraé su color dominante.
- **Paleta completa automática** — A partir de un color, genera una paleta armoniosa completa.
- **Color secundario configurable** — Elegí el color secundario que acompañe a la paleta.
- **Colores semánticos** — Genera automáticamente colores para sombras, Info, Warning, Error y Success.
- **Vista previa en plantillas** — Visualizá la paleta aplicada en distintas plantillas web (cards, formularios, botones, layouts, etc.).
- **Exportación múltiple** — Exportá la paleta en los formatos que necesites:
  - CSS
  - Tailwind
  - Prompt
  - PNG (para usar con color picker)

## Tecnologías

- [Astro](https://astro.build)

## Desarrollo

```sh
pnpm install
pnpm dev
```

El servidor de desarrollo se inicia en `localhost:4321`.

## Build

```sh
pnpm build
```

Genera los archivos estáticos en `dist/`.
