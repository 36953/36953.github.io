# 36953's blog

静态博客与自做工具，托管于 [GitHub Pages](https://36953.github.io/)。

## 本地预览

在仓库根目录启动任意静态服务器即可，例如：

```bash
python -m http.server 8000
```

## 发一篇新文章

1. 复制 `posts/_template.html`，另存为例如 `posts/my-topic.html`（不要用下划线开头）
2. 按文件里的注释改：摘要、标题、日期、正文
3. 把文件发给我，或放进 `posts/`；我会补首页入口并推送

首页列表格式（日期新的在上）：

```html
<li>
  <span class="post-meta">2024-03-18</span>
  <a class="post-link" href="/posts/my-topic.html">文章标题</a>
</li>
```

## 加一个工具

1. 在 `tools/` 下新建目录和 `index.html`
2. 在首页 Tools 列表与 `tools/index.html` 各加一条入口

## 目录

```
index.html          首页（文章 + 工具）
about/              关于
posts/              文章
tools/              工具
assets/main.css     站点样式
```
