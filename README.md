# 张博凯个人项目展示网站

这是一个单页式个人展示网站，用于展示个人基础信息、简历入口、AI 项目演示以及后续软件项目作品集内容。网站采用静态 HTML、CSS、JavaScript 构建，可以直接部署到 GitHub Pages。

## 页面内容

- 个人基本信息与求职方向
- 教育背景、专业技能、荣誉经历
- AI 项目展示区：3D 旅行足迹地图
- PDF 简历下载 / 查看入口
- 软件项目展示预留区，后续可继续补充项目卡片

## 技术栈

- HTML5
- CSS3
- JavaScript
- 静态资源：PDF、PNG 图片

## 项目结构

```text
.
|-- index.html
|-- README.md
|-- assets
|   |-- docs
|   |   `-- zhang-bokai-resume-it.pdf
|   `-- media
|       |-- ai-demo-preview.png
|       `-- travel-footprint-map.mp4
|-- css
|   `-- style.css
`-- js
    `-- main.js
```

## 本地预览

直接用浏览器打开 `index.html` 即可预览页面。

如果使用 VS Code，也可以通过 Live Server 插件启动本地服务查看。

## GitHub Pages 部署

1. 将项目推送到 GitHub 仓库。
2. 进入仓库的 `Settings`。
3. 找到 `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. 分支选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub Pages 自动部署。

部署完成后，GitHub 会生成一个公开访问链接。

## 大文件说明

当前项目中包含 `assets/media/travel-footprint-map.mp4`，文件体积较大。GitHub 普通仓库不适合直接提交超过 100 MB 的文件。

目前网站实际展示使用的是：

```text
assets/media/ai-demo-preview.png
```

点击图片会跳转到 Bilibili 在线演示链接。因此，如果准备推送到 GitHub，可以考虑删除本地 MP4，或者使用 Git LFS 管理该视频文件。

## 后续维护

后续添加软件项目时，可以在 `index.html` 的“软件项目展示预留区”中继续补充项目卡片，包括：

- 项目名称
- 项目简介
- 技术栈
- 个人职责
- 项目截图或演示链接
- 成果数据
