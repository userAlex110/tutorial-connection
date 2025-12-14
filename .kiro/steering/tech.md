# Technology Stack

## Architecture

**Static Site Generator Approach**: Next.js with static export for optimal performance, SEO, and hosting flexibility.

## Core Technologies

- **Framework**: Next.js 14+ with App Router
- **Language**: TypeScript for type safety and better developer experience
- **Styling**: Tailwind CSS for consistent, utility-first design
- **Content**: Markdown for simple, focused content
- **State Management**: Minimal client-side state (theme, navigation)
- **Testing**: Basic component testing with Jest + React Testing Library

## Development Tools

- **Package Manager**: npm or yarn
- **Code Quality**: ESLint + Prettier + Husky git hooks
- **Type Checking**: TypeScript strict mode
- **Build Tool**: Next.js built-in bundler (Webpack/Turbopack)

## Deployment & Hosting

- **Primary**: Vercel (recommended for Next.js)
- **Alternatives**: Netlify, GitHub Pages
- **CDN**: Automatic via hosting platform
- **Domain**: Custom domain support

## Common Commands

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run export       # Generate static export

# Testing
npm test             # Run unit tests
npm run test:watch   # Run tests in watch mode
npm run test:coverage # Generate coverage report

# Code Quality
npm run lint         # Run ESLint
npm run lint:fix     # Fix linting issues
npm run format       # Format code with Prettier
npm run type-check   # Run TypeScript compiler

# Property Testing
npm run test:property # Run property-based tests
```

## Data Storage

- **Client-Side**: localStorage + IndexedDB for user progress and preferences
- **Content**: Static files (Markdown/MDX) in repository
- **No Backend**: Fully client-side application for privacy

## Browser Support

- Modern browsers (ES2020+)
- Progressive enhancement for older browsers
- Mobile-responsive design
