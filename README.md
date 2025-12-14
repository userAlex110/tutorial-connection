# 真诚连接

用理工男能理解的方式，讲清楚人际关系这件事。

## 快速开始

```bash
# 安装依赖
pip install mkdocs-material

# 本地预览
mkdocs serve

# 构建静态站点
mkdocs build
```

## 部署到 GitHub Pages

```bash
mkdocs gh-deploy
```

## 内容结构

- `docs/articles/` - 文章（自我认知、沟通技巧等）
- `docs/guides/` - 实用指南
- `docs/resources/` - 推荐资源

## 贡献

欢迎提交 PR 贡献内容！

## License

MITr
pnpm install

```

3. **Start development server**
```bash
npm run dev
```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Production Build

```bash
# Build for production
npm run build

# Start production server
npm run start

# Or generate static export
npm run export
```

## 📁 项目结构

```
authentic-connections/
├── src/                     # 源代码
│   ├── app/                 # Next.js App Router 页面
│   ├── components/          # React 组件
│   └── lib/                 # 工具函数
├── content/                 # 文档内容 (Markdown)
│   ├── articles/            # 文章
│   ├── guides/              # 指南
│   └── resources/           # 资源
├── public/                  # 静态资源
└── docs/                    # 项目文档
```

## 🛠️ 可用脚本

- `npm run dev` - 启动开发服务器
- `npm run build` - 构建生产版本
- `npm run export` - 生成静态文件
- `npm run lint` - 运行代码检查
- `npm run format` - 格式化代码

## 🎨 技术栈

- **框架**: Next.js 14 with App Router
- **语言**: TypeScript
- **样式**: Tailwind CSS
- **内容**: Markdown
- **代码质量**: ESLint + Prettier

## 📖 核心理念

- **真诚第一**: 帮助用户在保持真实自我的基础上成长
- **内容为王**: 专注于有价值的知识和经验分享
- **简洁实用**: 避免复杂功能，专注于内容的呈现和阅读体验
- **开源协作**: 欢迎社区贡献内容和改进

## 🚀 Deployment

### Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/authentic-connections)

1. Fork this repository
2. Connect your GitHub account to Vercel
3. Import the project
4. Deploy automatically

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/your-username/authentic-connections)

1. Fork this repository
2. Connect to Netlify
3. Set build command: `npm run build && npm run export`
4. Set publish directory: `out`

### GitHub Pages

1. Fork this repository
2. Enable GitHub Actions in your repository
3. Push to main branch to trigger deployment
4. Access your site at `https://your-username.github.io/authentic-connections`

### Manual Deployment

```bash
# Generate static files
npm run export

# Upload the 'out' directory to your hosting provider
```

## 🛠️ Development

### Environment Setup

```bash
# Install dependencies
npm install

# Set up git hooks
npm run prepare

# Run type checking
npm run type-check

# Run linting
npm run lint
```

### Testing

```bash
# Run all tests
npm run test:all

# Run specific test types
npm run test:unit          # Unit tests
npm run test:property      # Property-based tests
npm run test:integration   # Integration tests

# Watch mode
npm run test:watch

# Coverage report
npm run test:coverage
```

### Code Quality

```bash
# Format code
npm run format

# Fix linting issues
npm run lint:fix

# Type checking
npm run type-check
```

## 🤝 Contributing

We welcome contributions! Please read our [Contributing Guide](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before submitting pull requests.

### Quick Contribution Steps

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Run tests: `npm run test:all`
5. Commit changes: `git commit -m 'Add amazing feature'`
6. Push to branch: `git push origin feature/amazing-feature`
7. Open a Pull Request

## 📚 Documentation

- [Developer Guide](docs/DEVELOPER_GUIDE.md)
- [Contributing Guide](CONTRIBUTING.md)
- [Deployment Guide](docs/DEPLOYMENT.md)
- [API Documentation](docs/API.md)

## 🐛 Issues & Support

- [Report a Bug](https://github.com/your-username/authentic-connections/issues/new?template=bug_report.md)
- [Request a Feature](https://github.com/your-username/authentic-connections/issues/new?template=feature_request.md)
- [Ask a Question](https://github.com/your-username/authentic-connections/discussions)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Tested with [Jest](https://jestjs.io/) and [fast-check](https://fast-check.dev/)
- Deployed on [Vercel](https://vercel.com/)
