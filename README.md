# 520 Gift Page

这是一个可以直接发布到 GitHub Pages 的静态网页，不需要安装依赖，也不需要启动本地服务。

## 建议上传到 GitHub 的内容

保留这些文件和文件夹即可：

- `index.html`
- `chat_stats.js`
- `imgs/`
- `TizzyT - 100.wav`
- `.nojekyll`
- `.github/workflows/deploy-pages.yml`
- `README.md`

这些内容不建议公开上传：

- `LTJL/`
- `scripts/`
- 原始聊天记录
- 调试视频和日志文件
- `TizzyT - 100.flac`

## 发布步骤

1. 在 GitHub 新建一个仓库。
2. 把这个目录推送到仓库，默认分支用 `main`。
3. 打开仓库的 `Settings` -> `Pages`。
4. 在 `Source` 里选择 `GitHub Actions`。
5. 等待 Actions 跑完，就会得到一个公开链接。

## 页面链接格式

发布成功后，链接通常会是：

`https://你的用户名.github.io/仓库名/`

## 备注

- 页面使用相对路径，适合直接放在 GitHub Pages。
- 已经加入 `.nojekyll`，不会被 Jekyll 处理。
- 已经加入自动部署工作流，后续只要 push 到 `main` 就会自动更新页面。
