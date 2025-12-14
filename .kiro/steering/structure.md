# Project Structure

## Root Directory Organization

```
authentic-connections/
├── .kiro/                    # Kiro configuration and specs
│   ├── specs/               # Project specifications
│   └── steering/            # AI assistant guidance rules
├── src/                     # Source code
│   ├── app/                 # Next.js App Router pages
│   ├── components/          # React components
│   └── lib/                 # Utility functions
├── content/                 # 文档内容 (Markdown)
│   ├── articles/            # 文章
│   ├── guides/              # 指南
│   └── resources/           # 资源
├── public/                  # Static assets
└── docs/                    # Documentation
```

## Source Code Structure

### Components Organization

- **Layout Components**: Header, Navigation, Footer, MainLayout
- **Content Components**: DocumentRenderer, ArticleList
- **UI Components**: Button, Card, Modal, ThemeToggle, LoadingSpinner, ErrorBoundary

### Content Structure

```
content/
├── articles/
│   ├── self-awareness/
│   │   ├── understanding-yourself.md
│   │   └── building-confidence.md
│   ├── communication/
│   │   ├── active-listening.md
│   │   └── expressing-emotions.md
│   └── relationships/
│       ├── authentic-connections.md
│       └── maintaining-friendships.md
├── guides/
│   ├── getting-started.md
│   └── practical-tips.md
└── resources/
    ├── books.md
    ├── tools.md
    └── external-links.md
```

## Key Architectural Patterns

### Data Flow

- **Content**: Static Markdown files → Build-time processing → Client-side rendering
- **Theme**: localStorage for dark/light mode preference

### Component Patterns

- **Container/Presentational**: Separate data logic from UI rendering
- **Compound Components**: Card components with multiple sub-components

### File Naming Conventions

- **Components**: PascalCase (e.g., `DocumentRenderer.tsx`)
- **Utilities**: camelCase (e.g., `contentParser.ts`)
- **Content**: kebab-case (e.g., `understanding-yourself.md`)

## Configuration Files Location

- **Next.js**: `next.config.js` in root
- **TypeScript**: `tsconfig.json` in root
- **Tailwind**: `tailwind.config.js` in root
- **Linting**: `.eslintrc.json` and `.prettierrc`
