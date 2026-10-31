# Pankaj Portfolio

Minimal React + TypeScript foundation built with Vite, Tailwind CSS, and ESLint.
The app currently displays only "Pankaj — Portfolio".

## Prerequisites

- Node.js 24 LTS
- pnpm 11 (the package manager used for this project)

## Installation

From the project directory:

```sh
pnpm install
```

## Development

```sh
pnpm dev
```

Open the local URL printed by Vite.

## Lint

```sh
pnpm lint
```

## Production build

```sh
pnpm build
```

TypeScript is checked before Vite builds the app. Output is written to `dist/`.

To preview the production build locally:

```sh
pnpm preview
```

## Structure

- `src/App.tsx`: minimal application component
- `src/main.tsx`: React entry point
- `src/index.css`: Tailwind CSS import
- `index.html`: HTML entry point
- `vite.config.ts`: React and Tailwind Vite plugins
- `eslint.config.js`: TypeScript and React lint rules
- `tsconfig*.json`: application and tooling TypeScript configuration

Tailwind uses its Vite plugin and CSS import; no extra Tailwind or PostCSS configuration is needed.
