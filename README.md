## Fast React Pizza Co. (React + Vite)

Fast React Pizza Co. is a small demo storefront built with React and Vite. It showcases a simple menu of pizzas, client-side rendering with React, and static assets served from the project `public/` folder.

This README shows how to run the project locally, build it for production, and deploy it to GitHub Pages.

### Quick summary

- Framework: React 19
- Bundler/dev server: Vite
- Repo title: Fast React Pizza Co. (see `index.html`)

## Features

- Simple React component structure (Header, Menu, Footer, Pizza)
- Static assets in `public/pizzas/` used by the menu
- Vite for fast dev server and production builds

## Prerequisites

- Node.js 16+ (Node 18+ recommended)
- npm (or yarn/pnpm)

## Install

Run in the project root:

```bash
npm install
```

## Development

Start the Vite dev server (hot reload):

```bash
npm run dev
```

Open your browser at http://localhost:5173 (Vite will print the exact URL).

## Build & Preview

Create an optimized production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```
