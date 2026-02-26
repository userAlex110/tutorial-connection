# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

这是一个基于 MkDocs Material 构建的开源文档网站，主题是用"工程学思维"讲解人际关系和脱单指南，面向理工科背景人群。

站点地址：https://useralex110.github.io/tutorial-connection/

## 常用命令

```bash
# 安装依赖
pip install -r requirements.txt

# 本地预览（开发时常用）
mkdocs serve

# 构建静态站点
mkdocs build

# 部署到 GitHub Pages
mkdocs gh-deploy
```

## 项目结构

- `docs/` - 所有文档内容目录
  - `index.md` - 首页
  - `basics/` - 基础理念文章
  - `self/` - 自我认知相关内容
  - `communication/` - 沟通技巧
  - `resources/` - 资源推荐
  - `articles/` - 其他文章
- `mkdocs.yml` - MkDocs 配置文件，定义导航、主题等
- `requirements.txt` - Python 依赖（仅 mkdocs-material）
- `.github/workflows/publish.yml` - GitHub Actions 自动部署配置

## 内容规范

- 使用中文书写
- 文档采用 Markdown 格式
- 使用 Material 主题扩展语法（如 `!!! tip`、`=== "Tab"` 等）
- 代码块支持语法高亮

## 部署说明

- 推送到 `main`/`master`/`releases/**` 分支会自动触发 GitHub Actions 部署
- 手动部署可运行 `mkdocs gh-deploy`
