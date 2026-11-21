---
name: opendraw
description: Reusable numbered image style presets. Select STYLE-001 and follow the full prompt and constraints in its style file.
---

# OpenDraw 绘图风格技能库

当用户说“使用风格001”“STYLE-001”或“几何解构拼贴海报”时，读取 `styles/style-001/STYLE.md` 并遵循完整提示词。多张照片逐张单独出稿，不拼接。

## 通用规则
- 保留源照片主体身份、姿势、重要环境特征。
- 用户的具体要求优先于预设中的可选文字排版；除非明确要求，不修改固定画幅和上下50%结构。
- 新增风格使用 `styles/style-002/STYLE.md` 等路径，并更新索引。
- 本仓库提供可移植提示词，不代表已经安装到某个绘图平台。

## 风格索引
| 编号 | 名称 | 文件 |
|---|---|---|
| STYLE-001 | 几何解构拼贴海报 | `styles/style-001/STYLE.md` |
