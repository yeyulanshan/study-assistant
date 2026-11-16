# 学习助手 · 展示页

一台会平衡的桌面学习助手，本科毕业设计展示页（可交互）。

- 展示页：https://yeyulanshan.github.io/study-assistant/
- 学习台原型：study-desk.html
- 电源板 3D 爆炸图：power-board-3d.html（六页评审版 P1–P5 + P4b）
- 整机 3D 爆炸图：whole-machine-3d.html（真实外壳模型，8 个部件可拆）

页面为单文件 HTML + 静态资源，无框架、无外部依赖；字体为 Noto Serif SC / Noto Sans SC 的子集，随页面分发。

## 结构

- `index.html` — 展示页（右侧展台随滚动换展品；「一句话 / 拆成动作」可交互）
- `study-desk.html` — 学习台原型（今日 / 章节 / 专注 / 收束 / 复习）
- `power-board-3d.html` — 电源板 3D 爆炸图（拖动旋转 / 滑块拉开 / 标签）
- `whole-machine-3d.html` — 整机 3D 爆炸图（真实外壳 GLB，8 个部件）
- `mainboard-layers.html` — 主板分层图
- `assets/` — 图片与字体子集

## 说明

展示页里的图片均来自项目自己的渲染、截图和 KiCad 导出图；样机尚未装配，页面中的性能数字是设计值，实测数据等样机。
