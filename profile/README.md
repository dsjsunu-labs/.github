# dsjsunu-labs

一些做成单个页面、打开就能用的小东西。

**全部 MIT 开源 · 没有后端 · 数据只留在你自己的浏览器里。**

## 项目

| | 项目 | 一句话 | 在线试玩 | 源码 |
| :--: | --- | --- | --- | --- |
| 🎄 | **心愿树** · Wish Tree | 挂照片或文字礼物，五种风格，许愿与烟花 | [打开](https://dsjsunu-labs.github.io/wish-tree/) | [wish-tree](https://github.com/dsjsunu-labs/wish-tree) |
| 🎰 | **银河弹珠局** · Galaxy Marble Club | 投币、随机倍率、弹簧杆控力、12 灯道与星卡 | [打开](https://dsjsunu-labs.github.io/galaxy-marble/) | [galaxy-marble](https://github.com/dsjsunu-labs/galaxy-marble) |
| 🎨 | **留白 · 填色实验室** · Liubai Coloring | 28 套配色、四种填色玩法、手机壁纸导出 | [打开](https://dsjsunu-labs.github.io/liubai-coloring/) | [liubai-coloring](https://github.com/dsjsunu-labs/liubai-coloring) |
| 🏠 | **我们的小屋** · Our Little House | 双人状态、报备、日历、月度回忆，只存本机 | [打开](https://dsjsunu-labs.github.io/our-little-house/) | [our-little-house](https://github.com/dsjsunu-labs/our-little-house) |
| 📚 | **AI 训练师三级刷题** · Level-3 Quiz | 900 题、错题本、模拟考试、番茄钟、离线可用 | [打开](https://dsjsunu-labs.github.io/ai-trainer-level3-quiz/) | [ai-trainer-level3-quiz](https://github.com/dsjsunu-labs/ai-trainer-level3-quiz) |

> 旧地址 `dsjsunu.github.io/<项目>/` 会自动跳到上面的新地址，入口页在 **[dsjsunu.github.io](https://dsjsunu.github.io/)**。

## 微信小程序版

其中两个项目附带原生微信小程序版本，代码在各仓库的 `miniprogram/` 目录，用微信开发者工具导入即可（AppID 默认是游客模式 `touristappid`）：

- [liubai-coloring/miniprogram](https://github.com/dsjsunu-labs/liubai-coloring/tree/main/miniprogram) — 原生 WXML + Canvas 2D 填色
- [galaxy-marble/miniprogram](https://github.com/dsjsunu-labs/galaxy-marble/tree/main/miniprogram) — 竖屏弹珠机

## 共同点

- **纯静态**：原生 HTML / CSS / JS 或 Canvas，没有构建步骤，没有服务器，没有 npm 依赖。
- **双击即用**：下载后打开 `index.html` 就能用；需要完整离线/安装能力的项目额外提供 `start.bat`。
- **本地优先**：记录、照片、进度都存在浏览器 `localStorage`，不上传任何服务器。
- **MIT**：代码可自由使用、修改、商用；少数项目的题库/笔记内容单独注明版权。

## 下载

每个仓库的 **Releases** 里都有一个 zip：下载 → 解压 → 双击 `index.html`。

也可以在 **[dsjsunu.github.io](https://dsjsunu.github.io/)** 用在线版，手机可以“添加到主屏幕”。

## 技术

| 项目 | 技术点 |
| --- | --- |
| 心愿树 | 60 个 SVG 渐变泡泡、CSS 变量主题、运行时生成礼物 SVG、WebAudio 合成音乐 |
| 银河弹珠局 | Canvas 物理与碰撞、弹簧杆蓄力、卡片抽取动画、响应式机台 |
| 留白填色 | 随机碎形（Voronoi）、Canvas 纹理、OKLab 配色、壁纸导出 |
| 我们的小屋 | 单文件应用 + 构建脚本、localStorage 数据模型、手绘 SVG 角色 |
| 刷题站 | PWA / Service Worker 离线、Supabase 可选同步、纯静态部署 |

## 许可

[MIT](https://github.com/dsjsunu-labs/wish-tree/blob/main/LICENSE)。每个仓库各自带一份 `LICENSE`。
