# Tooluse Labs Logo V2 Design Notes

## 结论

当前 logo 的方向可以保留：深色底、代码括号、暖色焦点，都符合 Tooluse Labs “为 AI agents 提供工具、MCP servers、skills 与支撑工具”的定位。

主要优化空间不在于重做品牌，而在于提升小尺寸识别度和语义清晰度。现有三点横排容易被理解为“输入中”或“加载中”，和 “tool use / tool routing / function call” 的关系需要解释后才成立。

本地已整理一版 v2 候选稿：

- `assets/brand/avatar-v2.svg`
- `assets/brand/avatar-v2-1024.png`
- `assets/brand/avatar-v2-460.png`
- `assets/brand/avatar-v2-circle-preview.png`

## 现版保留点

1. 代码括号

   方括号能够直接连接到开发者语境，也和 `tool(args)` / 参数槽位 / 工具调用列表相关。它是现有 logo 最值得保留的记忆点。

2. 深色底

   深色底适合 GitHub、终端工具、MCP、性能分析等开发者工具场景，也能让青色和琥珀色在头像尺寸下保持可见。

3. 青色 + 琥珀色

   青色负责技术感和边界结构，琥珀色负责视觉焦点。相比常见的黑白、紫蓝渐变、橙色 AI 品牌，这组颜色有一定区分度。

## 现版问题

1. 三点横排语义偏弱

   横向三点更常见的语义是 loading、typing、more menu。它不是错误，但对 “agent tool call” 的联想不够直接。

2. 品牌识别依赖解释

   现版需要通过 README 中的设计说明才能理解为 `tool(args)`。在 GitHub 头像、favicon、社媒头像等低上下文位置，用户只会看到 “[...]”。

3. 大尺寸略显静态

   当前版本非常干净，但缺少一点层次。作为 org avatar 没问题，作为品牌主视觉时稍弱。

## V2 设计方向

V2 不推翻现有品牌语言，而是在原结构内做三处收敛：

1. 保留括号轮廓

   继续使用左右代码括号作为核心外形，让新旧版本之间有继承关系。

2. 将三点改为三节点调用图

   内部符号从横向省略号改为连接的三节点图形。它仍然保持“三个工具/参数/选项”的数量感，但语义更接近：

   - agent 在多个工具之间路由
   - tool call graph
   - MCP/tool server 的连接关系
   - 从候选工具中选择并调用

3. 增加克制的层次

   背景加入非常轻的深色渐变和低对比内描边。它在大尺寸下更精致，但不会让小尺寸依赖复杂细节。

## 视觉规范

- 背景：深青黑渐变，保持开发者工具气质。
- 主结构：青色括号，继续作为第一识别层。
- 焦点：琥珀色节点，用于表达工具候选、调用节点、选择结果。
- 形状：圆角方底，兼容 GitHub 圆形头像裁切。
- 小尺寸优先级：先读出括号，再读出内部节点图；渐变和内描边只是辅助。

## 使用建议

如果要更新 GitHub org avatar，优先上传：

`assets/brand/avatar-v2-1024.png`

上传前建议对照：

`assets/brand/avatar-v2-circle-preview.png`

如果评审后采用 v2，可以再把 `assets/brand/avatar-v2.svg` 合并为新的 canonical `assets/brand/avatar.svg`，并重新生成 canonical PNG。当前这版先作为候选稿保留，避免直接覆盖线上正在使用的品牌资产。

## 不建议的方向

1. 不建议加入完整文字

   GitHub 头像尺寸较小，`Tooluse Labs` 文字会损失可读性，也会降低符号的独立识别。

2. 不建议改成通用 AI 星光/机器人图标

   这会进入高度同质化的 AI 品牌视觉，反而削弱 “tools / MCP / agent infra” 的专业定位。

3. 不建议使用复杂 3D 或多层光效

   头像场景需要稳、清楚、可复现。复杂效果在 32px 到 64px 下会变成噪声。
