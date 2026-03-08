# AVL Explorer

> An interactive AVL tree visualizer built with React, TypeScript, and Tailwind CSS.

![AVL Explorer](https://img.shields.io/badge/React-18-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript)
![Vite](https://img.shields.io/badge/Vite-5.0-purple?logo=vite)

## Features

- **Learn Mode** — Understand AVL tree rotations with step-by-step visualizations
- **Play Mode** — Test your knowledge with interactive challenges
- **Claymorphism Design** — Modern, soft UI with depth and shadows
- **Smooth Animations** — Fluid transitions powered by Framer Motion
- **Fully Responsive** — Works seamlessly on desktop and mobile

## Tech Stack

- **Framework:** React 18 + TypeScript
- **Build Tool:** Vite
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Animations:** Framer Motion

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or bun

### Installation

```bash
# Clone the repository
git clone https://github.com/MrAbhiudaySingh/avl-explorer.git
cd avl-explorer

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:8080](http://localhost:8080) in your browser.

## Building for Production

```bash
npm run build
```

The build output will be in the `dist/` directory.

## Deployment

### Vercel (Recommended)

This project is ready for Vercel deployment:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

Or deploy via CLI:

```bash
npm i -g vercel
vercel
```

### Other Platforms

The `dist/` folder contains static files ready for any static hosting service:
- Vercel
- Netlify
- GitHub Pages
- AWS S3 + CloudFront

## Project Structure

```
├── public/          # Static assets
├── src/
│   ├── components/  # React components
│   ├── pages/       # Page components
│   ├── hooks/       # Custom React hooks
│   └── lib/         # Utility functions
├── index.html       # Entry HTML
└── vite.config.ts   # Vite configuration
```

## License

MIT License — feel free to use this project for learning and teaching purposes.

---

Built with ❤️ by [Abhiuday Singh](https://github.com/MrAbhiudaySingh)
