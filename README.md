# Tech Gallery · 技术图解馆

[![在线查看](https://img.shields.io/badge/%E5%9C%A8%E7%BA%BF%E6%9F%A5%E7%9C%8B-Tech%20Gallery-0f6e56?style=for-the-badge\&logo=github)](https://siberiawool.github.io/TechGallery/)

[![License: MIT](https://img.shields.io/badge/License-MIT-5f5e5a.svg)](LICENSE)

交互式技术图解合集——AI 互连、光通信、半导体方向的可视化讲解，纯静态、无构建、可离线运行。


## 目录

| 图解                                              | 分类          | 简介                                                                  |
| ----------------------------------------------- | ----------- | ------------------------------------------------------------------- |
| [6D Torus 交互式 3D 演示](https://siberiawool.github.io/TechGallery/demos/6d-torus/index.html) | AI 互连 · 光通信 | Google TPU v9t 拓扑推演：64 机架全量渲染、12 条 ICI 电光分段、192 台 OCS、3D vs 6D 路径动画 |
| [可插拔、NPO、CPO结构图示](https://siberiawool.github.io/TechGallery/demos/cpo-evolution/index.html) | 光通信 · 光模块 | 光引擎位置演进：可插拔 → NPO → CPO，同一交换机主板视角下的三种光互连架构对比，含演进总览、9 维度对照表与三张同视角剖面结构图 |

## 仓库结构

```
TechGallery/
├── index.html      # 展馆主页（卡片目录 + 弹层预览，REGISTRY 注册表在内）
├── favicon.svg
├── .nojekyll       # 原样发布
├── demos/
│   ├── 6d-torus/   # 每篇图解 = 一个自包含文件夹
│   │   ├── index.html
│   │   └── three.module.js   # three.js r160 本地副本（无 CDN 依赖）
│   └── cpo-evolution/
│       ├── index.html
│       └── svg/   # 三张结构图（可插拔 / NPO / CPO）
├── .gitignore
├── LICENSE          # MIT
├── README.md
```

## 已知约定

- 所有图解内容为公开资料整理的技术推演，页面内标注口径与出处（如 6D Torus 为 SemiAnalysis 推演、谷歌未官宣）
- 不构成投资建议

## License

[MIT](LICENSE)
