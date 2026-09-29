# 原理图鉴 · 看得见的原理

交互式科普静态站点。每篇文章用「能动手玩的动画」讲清一个原理——拖动滑块、拨动开关，亲手把原理拆开再装回去。

**在线访问**：https://weather-source.github.io/principle-atlas/

## 文章列表

- [声音是怎么变成 MP3 的](articles/sound-to-mp3.html) —— 采样、量化、有损压缩，3 个交互演示
- [一张图片是怎么被压缩的](articles/image-compression.html) —— 色度抽样、DCT 分块量化，2 个交互演示（含迷你 JPEG 编码器）
- [手机是怎么知道你在哪的](articles/gps-positioning.html) —— 距离=速度×时间、三球交汇、时钟校准，1 个可拖拽演示
- [浏览器和你说的悄悄话，是怎么保密的](articles/https-encryption.html) —— 对称加密与 Diffie–Hellman 密钥交换，2 个交互演示

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
    ├── sound-to-mp3.html       # 第一期：数字音频
    ├── image-compression.html  # 第二期：图像压缩
    ├── gps-positioning.html    # 第三期：卫星定位
    └── https-encryption.html   # 第四期：网络加密
```

## License

MIT
