# Contributing to Authentic Connections

Thank you for your interest in contributing to Authentic Connections! This guide will help you get started with contributing to our open-source personal growth tutorial platform.

## 🌟 Ways to Contribute

- **Content Creation**: Write new tutorial modules, exercises, or resources
- **Code Improvements**: Enhance features, fix bugs, or improve performance
- **Documentation**: Improve guides, add examples, or translate content
- **Testing**: Add tests, report bugs, or improve test coverage
- **Design**: Improve UI/UX, create graphics, or enhance accessibility
- **Community**: Help others in discussions, review PRs, or moderate content

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- Git
- A GitHub account
- Basic knowledge of React, TypeScript, and Markdown

### Development Setup

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/authentic-connections.git
   cd authentic-connections
   ```

2. **Set up the development environment**
   ```bash
   # Install dependencies
   npm install
   
   # Set up git hooks
   npm run prepare
   
   # Start development server
   npm run dev
   ```

3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/bug-description
   # or
   git checkout -b docs/documentation-update
   ```

## 📝 Content Contributions

### Writing Tutorial Content

Content is stored in the `content/` directory using Markdown with frontmatter:

```markdown
---
title: 'Your Module Title'
description: 'Brief description of the module'
category: 'self-awareness' # or 'communication', 'relationships', etc.
difficulty: 'beginner' # or 'intermediate', 'advanced'
estimatedTime: 30 # minutes
prerequisites: ['module-id-1', 'module-id-2']
tags: ['tag1', 'tag2']
exercises:
  - type: 'reflection'
    title: 'Self-reflection exercise'
  - type: 'practice'
    title: 'Practical exercise'
lastUpdated: '2024-12-14'
contributors: ['your-github-username']
---

# Your Content Here

Write your tutorial content using Markdown...

## Exercises

Include practical exercises and reflection questions...
```

### Content Guidelines

- **Authenticity**: Focus on genuine growth, not manipulation tactics
- **Respect**: Use inclusive, respectful language
- **Practicality**: Include actionable exercises and real-world applications
- **Structure**: Follow the established content structure and formatting
- **Evidence-based**: Reference credible sources when making claims

## 💻 Code Contributions

### Code Style

We use automated tools to maintain code quality:

- **ESLint**: For code linting
- **Prettier**: For code formatting
- **TypeScript**: For type safety
- **Husky**: For git hooks

```bash
# Check code quality
npm run lint
npm run type-check

# Auto-fix issues
npm run lint:fix
npm run format
```

### Component Guidelines

- Use TypeScript for all components
- Follow the existing component structure
- Include proper prop types and documentation
- Ensure accessibility (ARIA labels, keyboard navigation)
- Write tests for new components

### Testing Requirements

All contributions must include appropriate tests:

```bash
# Run all tests
npm run test:all

# Run specific test types
npm run test:unit
npm run test:property
npm run test:integration

# Watch mode during development
npm run test:watch
```

#### Unit Tests
- Test component rendering and behavior
- Test utility functions
- Test error handling

#### Property-Based Tests
- Test universal properties across all inputs
- Use fast-check generators
- Follow the format: `**Feature: authentic-connections, Property X: description**`

## 🔄 Pull Request Process

### Before Submitting

1. **Test your changes**
   ```bash
   npm run test:all
   npm run lint
   npm run type-check
   npm run build
   ```

2. **Update documentation** if needed

3. **Add yourself to contributors** in relevant files

### PR Guidelines

1. **Clear title and description**
   - Use descriptive titles
   - Explain what changes you made and why
   - Reference any related issues

2. **Small, focused changes**
   - Keep PRs focused on a single feature or fix
   - Break large changes into smaller PRs

3. **Follow the template**
   - Fill out the PR template completely
   - Include screenshots for UI changes
   - List any breaking changes

### PR Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement
- [ ] Code refactoring

## Testing
- [ ] Tests pass locally
- [ ] Added new tests for changes
- [ ] Updated existing tests

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] No breaking changes (or documented)
```

## 🐛 Reporting Issues

### Bug Reports

Use the bug report template and include:

- **Environment**: OS, browser, Node.js version
- **Steps to reproduce**: Clear, numbered steps
- **Expected behavior**: What should happen
- **Actual behavior**: What actually happens
- **Screenshots**: If applicable
- **Additional context**: Any other relevant information

### Feature Requests

Use the feature request template and include:

- **Problem description**: What problem does this solve?
- **Proposed solution**: How should it work?
- **Alternatives considered**: Other approaches you've thought of
- **Additional context**: Examples, mockups, etc.

## 📚 Documentation

### Types of Documentation

- **User Documentation**: How to use the platform
- **Developer Documentation**: How to contribute and extend
- **API Documentation**: Technical reference
- **Deployment Documentation**: How to deploy and configure

### Documentation Standards

- Use clear, concise language
- Include code examples
- Add screenshots for UI features
- Keep documentation up-to-date with code changes
- Follow Markdown best practices

## 🎨 Design Contributions

### Design Guidelines

- **Accessibility**: WCAG 2.1 AA compliance
- **Responsive**: Mobile-first design
- **Performance**: Optimize images and assets
- **Consistency**: Follow existing design patterns
- **Simplicity**: Clean, minimal interface

### Assets

- Use SVG for icons when possible
- Optimize images (WebP format preferred)
- Follow naming conventions
- Include alt text for accessibility

## 🌍 Translation

We welcome translations to make the content accessible to more people:

1. **Check existing translations** in `content/locales/`
2. **Create language directory** following ISO 639-1 codes
3. **Translate content files** maintaining the same structure
4. **Update navigation** and metadata files
5. **Test the translation** thoroughly

## 📋 Code of Conduct

### Our Standards

- **Respectful**: Treat everyone with respect and kindness
- **Inclusive**: Welcome people of all backgrounds and experience levels
- **Constructive**: Provide helpful, actionable feedback
- **Professional**: Maintain professional communication
- **Growth-oriented**: Focus on learning and improvement

### Unacceptable Behavior

- Harassment, discrimination, or offensive language
- Personal attacks or trolling
- Spam or off-topic content
- Sharing private information without permission
- Any behavior that creates an unwelcoming environment

### Enforcement

Community leaders will:
- Remove inappropriate content
- Warn users about violations
- Temporarily or permanently ban repeat offenders
- Report serious violations to appropriate authorities

## 🏆 Recognition

Contributors are recognized in several ways:

- **Contributors list** in README and documentation
- **Commit attribution** in git history
- **Special mentions** in release notes
- **Contributor badges** on GitHub profile
- **Community highlights** in discussions

## 📞 Getting Help

- **Discussions**: Ask questions in GitHub Discussions
- **Issues**: Report bugs or request features
- **Discord**: Join our community chat (link in README)
- **Email**: Contact maintainers directly for sensitive issues

## 🔄 Release Process

### Versioning

We follow [Semantic Versioning](https://semver.org/):
- **MAJOR**: Breaking changes
- **MINOR**: New features (backward compatible)
- **PATCH**: Bug fixes (backward compatible)

### Release Schedule

- **Patch releases**: As needed for critical fixes
- **Minor releases**: Monthly for new features
- **Major releases**: Quarterly for significant changes

Thank you for contributing to Authentic Connections! Your efforts help create a better resource for personal growth and authentic relationships.