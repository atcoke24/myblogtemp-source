---
slug: tailwindcss-experience
title: tailwindcss-experience
authors: [yangshun]
tags: [experience, tailwindcss]
---

[Docusaurus blogging features](https://docusaurus.io/docs/blog) are powered by the [blog plugin](https://docusaurus.io/docs/api/plugins/@docusaurus/plugin-content-blog).

Simply add Markdown files (or folders) to the `blog` directory.

Regular blog authors can be added to `authors.yml`.

The blog post date can be extracted from filenames, such as:

- `2019-05-30-welcome.md`
- `2019-05-30-welcome/index.md`

A blog post folder can be convenient to co-locate blog post images:


The blog supports tags as well!

**And if you don't want a blog**: just delete this directory, and use `blog: false` in your Docusaurus config.

1. 使用 twin.macro
2. 去掉 vscode 中的 tailwind
3. 配置默认输出 rem 为 px：postcss-rem-to-responsive-pixel
4. 我想在 css 中使用括号语法
5. 使用 daisyui 以消减 tailwind 的复杂样式
6. @screen
7. tailwind 和 antd 的样式冲突解决