# Technology Stack

## Framework & Runtime
- **Next.js 15.4.3** - React framework with App Router
- **React 19.1.0** - Latest React with concurrent features
- **Node.js** - JavaScript runtime

## Styling & UI
- **Tailwind CSS v4** - Utility-first CSS framework
- **PostCSS** - CSS processing with Tailwind plugin
- **Geist Font Family** - Vercel's optimized fonts (Sans & Mono)
- **CSS Custom Properties** - For theme variables and design tokens

## Development Tools
- **ESLint** - Code linting with Next.js core web vitals config
- **Turbopack** - Fast bundler for development (--turbopack flag)

## Common Commands

### Development
```bash
npm run dev          # Start development server with Turbopack
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint checks
```

### Key Features Enabled
- App Router architecture (not Pages Router)
- Server Components by default
- Automatic font optimization
- Built-in dark/light theme support
- Image optimization via next/image

## Code Style Conventions
- Use ES modules (import/export)
- Prefer function declarations for React components
- Use Tailwind classes for styling
- Follow Next.js App Router patterns
- Maintain ESLint compliance