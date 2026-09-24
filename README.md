# Capitol Demo Concrete

Front-end marketing and interactive quote estimation demo for Capitol Demo Concrete, an Ottawa concrete and hardscape contractor concept. Built as an Omnivera front-end demo showcasing responsive design, multi-step quote wizards, and theme customization. Quote and contact forms stay on-device; nothing is submitted or emailed.

Live site: https://omniveraca.github.io/demo_concrete/

## Stack

- React 19 + TypeScript
- Vite 6
- Tailwind CSS 4
- Lucide React

## Local setup

Prerequisite: Node.js 20+ recommended.

```bash
git clone https://github.com/omniveraca/demo_concrete.git
cd demo_concrete
npm install
npm run dev
```

Vite serves the app at `http://localhost:5173`.

## Commands

```bash
npm run dev      # Vite development server
npm run build    # Production build to dist/
npm run preview  # Preview the production build
npm run lint     # Typecheck with tsc --noEmit
npm run clean    # Remove dist/
```

## Demo behaviour

- Quote and contact forms stay on-device. Nothing is submitted or emailed.
- Theme and announcement preferences use versioned `capitol-demo-*` local-storage keys.
- This demo is owned by [Omnivera](https://omnivera.pro).
