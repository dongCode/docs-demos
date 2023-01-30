---
slug: 入门
title: 入门
authors: d
tags: [测试标签, test, 小恐龙]
---

对 react 支持非常友好，Meta 负责主要维护开发


slug 必须有  slug: 入门  必须和文件夹 2023-01-30-入门 匹配，才能正确进入


title: 网页标题


基于插件，有丰富的插件扩展功能

编辑本页

点击编辑本页，跳转设置

![编辑按钮](./img1.png)

```javascript

presets: [
  [
    'classic',
    /** @type {import('@docusaurus/preset-classic').Options} */
    ({

      blog: {
        showReadingTime: true,
        // Please change this to your repo.
        // Remove this to remove the "edit this page" links.
        // 点击编辑本页需要跳转的地址
        editUrl:
          'https://github.com/dongCode/docs-demos/tree/main',
      },
    }),
  ],
],
```




[Docusaurus blogging features](https://docusaurus.io/docs/blog) are powered by the [blog plugin](https://docusaurus.io/docs/api/plugins/@docusaurus/plugin-content-blog).

Simply add Markdown files (or folders) to the `blog` directory.

Regular blog authors can be added to `authors.yml`.

The blog post date can be extracted from filenames, such as:

- `2019-05-30-welcome.md`
- `2019-05-30-welcome/index.md`

A blog post folder can be convenient to co-locate blog post images:

![Docusaurus Plushie](./docusaurus-plushie-banner.jpeg)

The blog supports tags as well!

**And if you don't want a blog**: just delete this directory, and use `blog: false` in your Docusaurus config.
