# Events Format

A static site built with React Router v7, Mantine UI, and TypeScript.

## Features

- ⚡️ React Router v7 (SSG/SPA mode)
- 🎨 Mantine UI components
- 📅 Mantine Dates (with dayjs)
- 🔔 Mantine Notifications
- 🎯 Tabler Icons
- 🐻 Zustand for state management
- 🔒 TypeScript
- ⚡️ Vite for fast development

## Getting Started

### Installation

```bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

### Building for Production

Create a production build:

```bash
npm run build
```

The build output will be in the `build/client` folder, ready to be deployed to any static hosting service.

### Type Checking

```bash
npm run typecheck
```

## Deployment

Deploy the `build/client` directory to any static hosting service:

- Netlify
- Vercel
- GitHub Pages
- Cloudflare Pages
- AWS S3 + CloudFront
