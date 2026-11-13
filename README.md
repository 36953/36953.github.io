# 36953's blog

静态博客与自做工具，托管于 [GitHub Pages](https://36953.github.io/)。

## 本地预览

在仓库根目录启动任意静态服务器即可，例如：

```bash
python -m http.server 8000
```

## 发一篇新文章

1. 复制 `posts/welcome.html` 为新文件
2. 修改标题、日期与正文
3. 在 `index.html` 的 Posts 列表最上方加一条链接

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
