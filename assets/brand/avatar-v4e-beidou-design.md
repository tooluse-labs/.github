# Tooluse Labs V4e Beidou Candidate

## 设计目标

这版在 V4/V4a 的括号系统里加入北斗七星图案，用“导航、定位、选择方向”的隐喻补充 Tooluse Labs 的 agent tool routing 定位。

当前版本已按七颗星的 J2000 RA/Dec 相对位置重新摆放，不再使用手工近似图形。投影方式为北向上、东向左的局部切平面投影；在 logo 中只做等比例缩放和平移，以适配括号内部安全区。

北斗七星的语义适合这里：

- agent 在工具空间中寻找正确方向。
- tool selection 像路径导航，而不只是静态工具列表。
- 北斗图形比普通网络节点更有记忆点。

## 视觉处理

- 外部继续使用青色代码括号，保持与现有品牌资产一致。
- 内部使用七个琥珀色星点，连接成北斗七星。
- 星点按实际观感做亮度分级：Dubhe、Alioth、Alkaid 更大，Merak、Phecda、Mizar 稍小，Megrez 最小。
- 连线做成较细的双层线：暗色底线负责结构，琥珀色细线负责可见性，避免小尺寸下变成粗重折线。
- 星点带深色描边，确保节点和连线分离，64px 下不糊成一串。
- 图案整体放在括号安全区内，避免 GitHub 圆形头像裁切。
- 星点按北斗一到北斗七顺次相连：Dubhe -> Merak -> Phecda -> Megrez -> Alioth -> Mizar -> Alkaid。不额外回连斗身闭合边，保持图形简洁。

## 风险

七个节点在 64px 以下会比 V4a 更复杂。作为品牌图案有记忆点，但如果只追求小尺寸极简识别，V4a 仍然更稳。

## 使用建议

这版适合用于更有东方导航隐喻的品牌方向，也适合 README 或官网视觉。若作为 GitHub org avatar，建议先对照：

- `assets/brand/avatar-v4e-beidou-circle-preview.png`
- `assets/brand/avatar-v4e-beidou-64px-sheet.png`
