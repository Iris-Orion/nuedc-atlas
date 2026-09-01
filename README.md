# 电赛赛题图谱 · NUEDC Atlas

全国大学生电子设计竞赛（NUEDC）2016–2026 共 11 届 104 道赛题，按 8 个命题方向重排的复习手册。

**在线阅读：https://iris-orion.github.io/nuedc-atlas/**

## 内容

总览页含命题密度矩阵（方向 × 届别）、8 个赛道入口、三阶段复习路线，以及可按方向筛选的全量赛题年表。

八个赛道各自成页：

| 赛道 | 题量 | 页面 |
|---|---|---|
| 电源与功率变换 | 17 | [tracks/1-power.html](tracks/1-power.html) |
| 测量与仪器仪表 | 20 | [tracks/2-measurement.html](tracks/2-measurement.html) |
| 信号源与信号处理 | 8 | [tracks/3-signal.html](tracks/3-signal.html) |
| 高频与无线通信 | 9 | [tracks/4-rf.html](tracks/4-rf.html) |
| 自动控制系统 | 9 | [tracks/5-control.html](tracks/5-control.html) |
| 移动机器人 · 小车 | 10 | [tracks/6-rover.html](tracks/6-rover.html) |
| 无人机与飞行器 | 9 | [tracks/7-uav.html](tracks/7-uav.html) |
| 传感 · 定位 · 嵌入式视觉 | 22 | [tracks/8-sensing.html](tracks/8-sensing.html) |

每个赛道页包含：该方向历年赛题 → **12 条知识点逐条解析** → 参考设计方案 → 开源工程 → 过关线。
知识点解析的固定结构是「概念 → 关键公式 → 方案对比 → 电赛怎么考（锚定真题指标）→ 常见坑」，
八个赛道合计 96 条、约 10 万中文字、526 个公式。

## 技术说明

- **纯静态**，无框架、无构建依赖、无外部请求（Google Fonts 除外）。
- 数学公式用 **KaTeX 在构建期预渲染**为静态 HTML，字体以 data URI 内联。
  页面运行时不加载任何 JS，离线打开也能正确显示公式。
- 支持浅色 / 深色双主题，跟随系统设置。
- 单页 250–430 KB（其中约 156 KB 是内联的 KaTeX 字体与样式）。

页面由脚本生成，源工程与赛题存档在本地另一个仓库，此处只发布站点产物。

## 版权

赛题内容版权归全国大学生电子设计竞赛组织委员会所有。本站为个人复习整理，
知识点解析、参考设计方案与开源项目推荐均为整理者归纳，非官方内容；
具体指标请以官方赛题原文为准。
