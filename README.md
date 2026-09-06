# My Blog

基于 [Astro](https://astro.build) 和 [Firefly](https://github.com/CuteLeaf/Firefly) 主题（MIT）搭建的极简个人博客，部署在 GitHub Pages。

**线上地址**：<https://lkdhhsh.github.io/my-blog/>

## 常用命令

```bash
pnpm install        # 安装依赖
pnpm dev            # 本地开发，http://localhost:4321
pnpm build          # 构建到 dist/
pnpm new-post 文章名 # 新建一篇文章
```

## 写文章

在 `src/content/posts/` 下新建 Markdown 文件：

```markdown
---
title: 文章标题
published: 2026-09-06
description: 文章摘要
tags: [标签]
category: 分类
---

正文使用 Markdown 书写。
```

推送后 GitHub Actions 会自动构建并发布。

## 目录说明

- `src/content/posts/` — 博客文章
- `src/content/spec/` — 关于页等固定页面
- `src/config/` — 全部站点配置（导航、侧栏、壁纸、评论等）

## 主题文档

更多主题功能（评论、统计、友链等）见 [Firefly 文档](https://docs-firefly.cuteleaf.cn)。
