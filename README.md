# Tech Gallery · 技术图解馆

![在线查看](https://img.shields.io/badge/%E5%9C%A8%E7%BA%BF%E6%9F%A5%E7%9C%8B-Tech%20Gallery-0f6e56?style=for-the-badge\&logo=github)



![License: MIT](https://img.shields.io/badge/License-MIT-5f5e5a.svg)

交互式技术图解合集——AI 互连、光通信、半导体方向的可视化讲解，纯静态、无构建、可离线运行。

> 点击上方「在线查看」直接体验渲染结果，无需下载。占位链接 `你的用户名` 替换为实际 GitHub 用户名即可。

## 目录

| 图解                                              | 分类          | 简介                                                                  |
| ----------------------------------------------- | ----------- | ------------------------------------------------------------------- |
| [6D Torus 交互式 3D 演示](demos/6d-torus/index.html) | AI 互连 · 光通信 | Google TPU v9t 拓扑推演：64 机架全量渲染、12 条 ICI 电光分段、192 台 OCS、3D vs 6D 路径动画 |

## 仓库结构

```
tech-gallery/
├── index.html      # 展馆主页（卡片目录 + 弹层预览，iframe 懒加载）
├── favicon.svg
├── .nojekyll       # 告诉 GitHub Pages 跳过 Jekyll，原样发布
├── demos/
│   └── 6d-torus/   # 每篇图解 = 一个自包含文件夹
│       ├── index.html
│       └── three.module.js   # three.js r160 本地副本（无 CDN 依赖）
├── .gitignore
├── LICENSE          # MIT
└── README.md
```

## 已知约定

- 所有图解内容为公开资料整理的技术推演，页面内标注口径与出处（如 6D Torus 为 SemiAnalysis 推演、谷歌未官宣）
- 不构成投资建议

## License

[MIT](LICENSE)
