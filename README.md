# 今天吃什么网站静态部署

这是 GitHub Pages 可直接部署的纯静态版本。

部署方式：
1. 将本文件夹内的所有文件提交到 GitHub 仓库。
2. 在 GitHub 仓库 Settings -> Pages 中选择部署分支和根目录。
3. 本版本已使用相对路径构建，适合部署到 `https://用户名.github.io/仓库名/` 这类子路径。

说明：
- `.nojekyll` 用于避免 GitHub Pages 对静态资源做 Jekyll 处理。
- `404.html` 已复制自 `index.html`，用于刷新或直接访问页面时兜底。
- 这是纯前端静态站点，不包含后端数据库。
