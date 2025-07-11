# Portfolio Website

A modern, elegant portfolio website built with React, TypeScript, and Vite.

## 🚀 Quick Start

### Prerequisites

- Node.js (v16 or higher)
- npm, yarn, or pnpm

### Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <your-repo-name>
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open [http://localhost:8080](http://localhost:8080) in your browser.

## 📦 Build for Production

```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

## 🚀 Deployment

### Deploy to Vercel

1. Install Vercel CLI:

```bash
npm i -g vercel
```

2. Deploy:

```bash
vercel
```

Or simply push to GitHub and connect your repository to Vercel for automatic deployments.

### Deploy to Netlify

1. Build the project:

```bash
npm run build
```

2. Deploy the `dist/` folder to Netlify.

### Deploy to GitHub Pages

1. Build the project:

```bash
npm run build
```

2. Deploy the `dist/` folder to your `gh-pages` branch.

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Core UI component library
│   └── sections/       # Page sections
├── pages/              # Route components
├── lib/                # Utility functions
├── hooks/              # Custom React hooks
├── App.tsx             # Main app component
└── main.tsx            # App entry point
```

## 🛠️ Built With

- **React 18** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **React Router** - Client-side routing
- **TailwindCSS** - Styling
- **Framer Motion** - Animations
- **Radix UI** - Accessible components
- **Lucide React** - Icons

## 📱 Features

- ✅ Fully responsive design
- ✅ Modern animations and transitions
- ✅ Optimized performance
- ✅ SEO friendly
- ✅ Accessible components
- ✅ Type-safe codebase
- ✅ Production-ready build

## 🎨 Customization

The design system can be customized through `tailwind.config.ts`. All colors, spacing, and design tokens are defined there.

## 📄 License

This project is licensed under the MIT License.
