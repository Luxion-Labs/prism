# Prismarine

> Fast, local-first API testing and debugging workbench built with Next.js and Bun.

![Prismarine Banner](assets/images/banner.svg)

<p align="center">
  <img src="https://img.shields.io/badge/Runtime-Bun-FBF0DF?style=for-the-badge&logo=bun&logoColor=black" alt="Bun">
  &nbsp;
  <img src="https://img.shields.io/badge/Frontend-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
  &nbsp;
  <img src="https://img.shields.io/badge/Language-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  &nbsp;
  <img src="https://img.shields.io/badge/State-Zustand-443E38?style=for-the-badge" alt="Zustand">
  &nbsp;
  <img src="https://img.shields.io/badge/Storage-100%25_Local-10B981?style=for-the-badge" alt="Local">
  &nbsp;
  <img src="https://img.shields.io/badge/SLA-24_Hours-8B5CF6?style=for-the-badge" alt="SLA">
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="MIT License"></a>
  &nbsp;
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/Contributions-Welcome-blueviolet?style=flat-square" alt="Contributing"></a>
</p>

---

## Quick Start & Getting Started

Getting Prismarine running locally takes only two steps:

```bash
git clone https://github.com/Luxion-Labs/prism.git
cd prism
bun install && bun run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Tech Stack

- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Package Manager**: Bun
- **Styling**: SCSS (structured architecture)
- **State Management**: Zustand
- **Desktop Integration**: Tauri (preparation in place)

## Setup

### Prerequisites
- Bun (https://bun.sh)

### Installation

```bash
bun install
```

### Development

```bash
bun run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build

```bash
bun run build
bun run start
```

### Linting

```bash
bun run lint
bun run lint:fix
```

## Project Structure

- `app/` - Next.js App Router pages and layouts
- `components/` - Reusable UI components (layout, ui)
- `features/` - Feature-specific business logic (types, stores, apis)
- `lib/` - Utilities, helpers, and Tauri integration
- `styles/` - SCSS with structured architecture (abstracts, base, components)
- `public/` - Static assets

## Features

- Clean feature-based architecture
- Type-safe state management with Zustand
- Structured SCSS with abstracts, base, and component styles
- ESLint configuration for code quality
- Production-ready setup

## License

Proprietary


---

## Maintainer Response SLA
Luxion Labs enforces a strict 24-hour response SLA on all community issues, feature proposals, and pull requests. See [CONTRIBUTING.md](CONTRIBUTING.md) for full development guidelines.

## License
Distributed under the MIT License. See [LICENSE](LICENSE) for details.
