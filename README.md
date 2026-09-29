# 原理图鉴 · 看得见的原理

交互式科普静态站点。每篇文章用「能动手玩的动画」讲清一个原理——拖动滑块、拨动开关，亲手把原理拆开再装回去。

**在线访问**：https://weather-source.github.io/principle-atlas/

## 文章列表

- [声音是怎么变成 MP3 的](articles/sound-to-mp3.html) —— 采样、量化、有损压缩，3 个交互演示

## 技术说明

- 纯静态：HTML + CSS + 原生 JS，无框架、无构建步骤、无后端
- 所有交互演示基于 SVG + 原生 JavaScript，在浏览器本地运行，零依赖
- 部署：GitHub Pages（main 分支根目录）

## 本地预览

直接用浏览器打开 `index.html`，或：

```bash
python -m http.server 8000
```

## 目录结构

```
principle-atlas/
├── index.html                  # 首页（文章目录）
├── assets/
│   └── style.css               # 全站样式
└── articles/
    └── sound-to-mp3.html       # 第一期：数字音频
```

## License

MIT
