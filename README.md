# Vite + React + TypeScript + Tailwind CSS v4 + shadcn/ui Template

This is a starter template for building modern React applications with Vite, TypeScript, Tailwind CSS v4, and shadcn/ui components.

## Features

- ⚡ Vite for fast development and building
- ⚛️ React 19 with TypeScript
- 🎨 Tailwind CSS v4 for styling
- 🧩 shadcn/ui components (Radix UI primitives)
- 📦 Pre-configured with ESLint and TypeScript
- 🚀 Ready-to-use setup with minimal configuration

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-template-repo.git
   cd your-template-repo
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
src/
├── components/
│   └── ui/          # shadcn/ui components
├── lib/
│   └── utils.ts     # Utility functions
├── App.tsx          # Main app component
├── main.tsx         # Entry point
└── index.css        # Global styles
```

## Adding shadcn/ui Components

To add more components from shadcn/ui:

```bash
npx shadcn@latest add [component-name]
```

## Customization

- Modify `tailwind.config.js` for Tailwind CSS configuration
- Update `components.json` for shadcn/ui settings
- Adjust TypeScript settings in `tsconfig.json`

## License

This template is open source and available under the [MIT License](LICENSE).
