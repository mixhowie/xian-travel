# 西安漫游

一个适配手机和桌面的西安旅行静态首页，包含景点、三日行程和美食推荐。

## 本地预览

在仓库目录运行 `python3 -m http.server 8000`，然后打开 http://localhost:8000。

## 自动部署

在 GitHub 的 **Settings → Pages → Build and deployment → Source** 中选择 **GitHub Actions**。

推送 `index.html` 或部署工作流到 `main` 分支后，GitHub Actions 会打包页面并部署到 GitHub Pages。也可以在 **Actions → Deploy website to GitHub Pages → Run workflow** 中手动触发。

预期网站地址为 https://mixhowie.github.io/xian-travel/，以部署任务输出的 URL 为准。

私有仓库使用 GitHub Pages 需要支持此功能的 GitHub 付费方案。网站公开访问与仓库可见性是不同的设置。
