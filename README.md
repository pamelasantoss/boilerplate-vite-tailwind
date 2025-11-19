# Boilerplate Vite + React + TypeScript + TailwindCSS

![GitHub repo size](https://img.shields.io/github/repo-size/pamelasantoss/boilerplate-vite-tailwind?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/pamelasantoss/boilerplate-vite-tailwind?color=%23387fc6&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/pamelasantoss/boilerplate-vite-tailwind?color=%23387fc6&style=for-the-badge)

## Description

This repository is a minimal starter boilerplate for building React applications with TypeScript using Vite and Tailwind CSS. It provides a small, well-configured base including build, linting and formatting scripts so you can quickly scaffold components and start development.

> **Note — HMR (Hot Module Replacement):** This template uses Vite's HMR to update modules without a full page reload, which speeds up development and can preserve application state when possible. For React, `@vitejs/plugin-react` integrates React Fast Refresh to help preserve component state. See Vite docs: https://vitejs.dev/guide/features.html#hot-module-replacement

What this boilerplate provides out of the box:
- Fast development server with `Vite` (`npm run dev`)
- React + TypeScript support (source files under `src/`)
- Tailwind CSS configured and imported in `src/styles/index.css`
- Minimal example component in `src/App.tsx` and entry point in `src/main.tsx`
- Useful scripts: `dev`, `build` (executes `tsc -b && vite build`), `lint`, `format` and `preview`

## Features
- Fast HMR-enabled (Hot Module Replacement) dev server via Vite
- Clean minimal template using React + TypeScript
- Tailwind CSS + PostCSS + Autoprefixer preconfigured
- ESLint for linting and Prettier for formatting
- `prepare` script present for Husky (git hooks initialization if configured)
- Minimal project structure ready for component development

## Technologies

- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Husky](https://typicode.github.io/husky/)

## Getting Started

### Prerequisites

- Node.js v19 or higher (or a compatible version of Node supported by your toolchain).

### Installation

1. Clone the repository and install dependencies:
  ```bash
  git clone https://github.com/pamelasantoss/boilerplate-vite-tailwind.git
  cd boilerplate-vite-tailwind
  npm install
  ```

2. Start the development server:
  ```bash
  npm run dev
  ```

Open `http://localhost:5173` in your browser.

### Production Build

```bash
npm run build
npm run preview
```

## Project Structure
- `src/`
  - `App.tsx` — example component
  - `main.tsx` — application entry point
  - `styles/index.css` — Tailwind CSS entry
- `vite.config.ts` — Vite configuration
- `tailwind.config.js` — Tailwind configuration
- `postcss.config.js` — PostCSS + Autoprefixer configuration
- `eslint.config.js` — ESLint configuration
- `package.json` — scripts and dependencies

## Learning Goals

This boilerplate aims to help developers learn and practice:
- Building React applications with TypeScript using Vite
- Using Tailwind CSS for utility-first styling and rapid prototyping
- Running and configuring development scripts (`dev`, `build`, `preview`)
- Applying linting and automatic formatting with `ESLint` and `Prettier`
- Integrating git hooks via `Husky` for improved code quality (optional)

Note: This is a minimal starter template — it does not include routing examples, tests, or CI workflows by default.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/pamelasantoss/boilerplate-vite-tailwind/blob/main/LICENSE) file for details.

---

Made with ❤️ by [Pamela Santos](https://pamelasantos.dev.br/)