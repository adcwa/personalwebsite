---
title: "私人博客 Hugo 快速复刻 Prompt"
date: 2025-06-19T22:30:00+08:00
draft: false
summary: "私人博客 Hugo 快速复刻 Prompt"
---
 


# 极简苹果风格私人博客 Hugo 快速复刻 Prompt

## 文章摘要

本篇文章总结了如何用 Hugo 快速搭建一个极简、苹果官网风格、支持本地 Markdown 内容维护、适配移动端、禁止搜索引擎收录的私人博客。文末附有一条可直接复用的 AI Prompt，助你一键复刻同款网站。

---

## 需求与风格

- 只为自己用，不公开、不分享、不被搜索引擎收录
- 内容通过本地 Markdown 文件维护
- 极简风格，参考苹果官网（Apple.com）设计
- 响应式，适配手机端
- 无需登录、评论、社交等功能
- 支持一键部署到 Vercel（或 Netlify 等平台）

---

## 技术选型

- 静态站点生成器：Hugo
- 主题：自定义极简苹果风格
- 内容维护：本地 Markdown
- 部署：Vercel 自动识别 Hugo，无需自定义 builder

---

## 复刻 Prompt（可直接用于 AI 或 Copilot）

```
请帮我设计并实现一个极简风格、苹果官网风格的私人博客网站，要求如下：

- 只为我个人使用，不对外公开，不需要登录、评论、社交等功能
- 内容通过本地 Markdown 文件维护，支持文章列表和详情页
- 整体风格极简，参考 Apple 官网，留白充足、优雅字体、黑白灰主色调、少量高质量图片
- 响应式设计，适配手机端
- 禁止搜索引擎收录（robots.txt 和 meta noindex）
- 使用 Hugo 作为静态站点生成器，自动生成静态页面
- 支持一键部署到 Vercel（或 Netlify），无需自定义 builder，直接让 Vercel 自动识别 Hugo 项目
- 提供 README，说明内容维护和部署流程

请直接生成项目结构、主题模板、基础样式、示例文章和 README，确保我只需写 Markdown 并 push 到 GitHub 即可一键上线。
```

---

## 快速搭建流程

1. 安装 Hugo 并初始化项目
2. 创建极简苹果风格主题（layouts、static/css、基础模板）
3. 配置 `config.toml`，设置 noindex、站点信息
4. 添加 `static/robots.txt` 禁止爬虫
5. 写 Markdown 文章，放入 `content/posts/`
6. 本地 `hugo server` 预览
7. push 到 GitHub，Vercel 自动识别并部署

---

## 结语

只需保存并复用上方 Prompt，每次都能一键生成同款极简苹果风格私人博客。  
如需自定义样式，编辑 `themes/minimal-apple/static/css/minimal-apple.css` 即可。

> 仅供个人使用，勿外传。

 