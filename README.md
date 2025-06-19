# 极简苹果风格 Hugo 博客

## 项目简介

本项目是一个极简风格、苹果官网风格的个人博客，基于 [Hugo](https://gohugo.io/) 静态站点生成器，支持本地 Markdown 内容维护，适配移动端，默认禁止搜索引擎收录，适合私人笔记和内容运营。

## 目录结构

- `content/`：存放你的 Markdown 文章
- `themes/minimal-apple/`：极简苹果风格主题
- `static/robots.txt`：禁止搜索引擎收录
- `config.toml`：站点配置
- `vercel.json`：Vercel 部署配置

## 内容维护

1. 在 `content/posts/` 目录下新建 Markdown 文件（如 `my-note.md`）。
2. 使用标准 Markdown 语法书写内容，支持标题、图片、代码块等。
3. 保存后本地运行 `hugo server` 预览效果。

## 本地预览

```bash
hugo server --buildDrafts --disableFastRender
```

浏览器访问 http://localhost:1313 查看。

## 一键部署到 Vercel

1. 注册并登录 [Vercel](https://vercel.com/)。
2. 新建项目，选择本仓库（或 push 到 GitHub 后导入）。
3. Vercel 会自动识别 `vercel.json` 并用 Hugo 构建，无需额外配置。
4. 部署完成后即可访问你的私人博客。

## 隐私说明

- 已配置 `robots.txt` 和 meta `noindex`，禁止搜索引擎收录。
- 仅凭不公开网址保证隐私，无需登录。

## 主题自定义

如需调整样式，可编辑 `themes/minimal-apple/static/css/minimal-apple.css`。

---

> 仅供个人使用，勿外传。 