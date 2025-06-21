# BA-Atelier Frontend

Este proyecto es el frontend de BA-Atelier, desarrollado con Astro, Tailwind CSS y TypeScript.

## Estructura del proyecto

- `src/` — Código fuente principal
  - `components/` — Componentes reutilizables
  - `layouts/` — Layouts de páginas
  - `pages/` — Páginas del sitio
  - `styles/` — Hojas de estilo globales y utilitarias
  - `assets/` — Imágenes y otros recursos
- `public/` — Archivos públicos y estáticos
- `astro.config.mjs` — Configuración de Astro
- `tailwind.config.mjs` — Configuración de Tailwind CSS
- `tsconfig.json` — Configuración de TypeScript
- `package.json` — Dependencias y scripts

## Scripts principales

- `pnpm install` — Instala las dependencias
- `pnpm dev` — Inicia el servidor de desarrollo
- `pnpm build` — Genera la versión de producción
- `pnpm preview` — Previsualiza la build de producción

## Requisitos

- Node.js >= 18
- pnpm >= 8

## Instalación

1. Clona el repositorio
2. Instala las dependencias:
   ```sh
   pnpm install
   ```
3. Inicia el entorno de desarrollo:
   ```sh
   pnpm dev
   ```

## Tecnologías principales

- [Astro](https://astro.build/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)

## Estructura de carpetas

```
Frontend/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   ├── Scripts/
│   └── styles/
├── astro.config.mjs
├── package.json
├── tailwind.config.mjs
├── tsconfig.json
└── ...
```

## Licencia

MIT
