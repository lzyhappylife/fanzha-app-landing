# 国家反诈中心 App · 产品宣传页

一个单文件、自包含的产品介绍落地页，用于介绍公安部官方「国家反诈中心 App」的核心功能、官方数据、反诈生态与下载方式。

## 在线预览

启用 GitHub Pages 后访问：`https://<你的用户名>.github.io/<仓库名>/`

## 本地运行

直接双击 `index.html` 在浏览器打开即可，无需构建、无需服务器。

## 技术栈

- 原生 HTML / CSS / JavaScript，零构建工具
- 动效库（CDN 引入）：[AOS](https://michalsnik.github.io/aos/) 滚动入场、[Hover.css](https://ianlunn.github.io/Hover/) 悬停、[Vanta.js](https://www.vantajs.com/) 粒子首屏、[anime.js](https://animejs.com/) 编排动画、[Lenis](https://github.com/studio-freight/lenis) 惯性滚动
- 响应式布局，适配桌面与移动端
- 自动尊重 `prefers-reduced-motion`

## 目录结构

```
.
├── index.html        # 主页面（自包含，样式与脚本内联）
├── assets/           # App 截图、图标、角色插画
│   ├── app-icon.png
│   ├── home-1080.png
│   ├── home-2024.png
│   ├── report-page.png
│   ├── news-page.png
│   ├── scammer.png   # 左下角悬浮骗子角色
│   └── police.png    # 右下角悬浮警官角色
├── LICENSE
└── README.md
```

## 数据来源

页面中的官方数据（预警次数、举报线索量、96110 / 12381 等）来源于公安部网站公开报道，仅作产品介绍用途，以官方发布为准。

## 开源协议

[MIT](./LICENSE)
