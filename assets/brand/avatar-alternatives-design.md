# Tooluse Labs Logo Alternatives

## 背景

当前 logo 已经有清晰的基础资产：深色底、青色代码括号、琥珀色焦点。其他方案不建议完全推翻这套视觉语言，而是围绕 “AI agents 使用工具” 这个定位，探索不同的内部符号。

本次补充三条额外方向，和已生成的 v2 一起比较：

- `avatar-v2.svg`：工具调用图
- `avatar-v3-monogram.svg`：品牌字母记忆点
- `avatar-v4-router.svg`：agent 路由选择
- `avatar-v5-prompt.svg`：开发者 CLI 调用

## 方案 A：V2 工具调用图

文件：

- `assets/brand/avatar-v2.svg`
- `assets/brand/avatar-v2-1024.png`
- `assets/brand/avatar-v2-460.png`
- `assets/brand/avatar-v2-circle-preview.png`

核心想法：保留括号，把三点从“省略号”改成“连接的工具调用图”。

优点：

- 继承现版最自然，新旧切换成本低。
- 比横向三点更接近 tool routing / tool call graph。
- 小尺寸仍能读出括号和三个节点。

风险：

- 三节点图仍有一定通用性，可能被理解为普通网络/关系图。

适合场景：

- 作为 GitHub org avatar 的默认推荐方案。

## 方案 B：V3 品牌字母记忆点

文件：

- `assets/brand/avatar-v3-monogram.svg`
- `assets/brand/avatar-v3-monogram-1024.png`
- `assets/brand/avatar-v3-monogram-460.png`
- `assets/brand/avatar-v3-monogram-circle-preview.png`

核心想法：在括号中放入抽象的 `T` 形节点标记，强化 Tooluse 的首字母记忆。

优点：

- 比节点图更品牌化，不只是功能示意。
- 在小尺寸下容易形成稳定轮廓。
- 适合未来扩展成产品图标或 favicon。

风险：

- `T` 和 tool use 的关系更依赖品牌名，不如 v2 直接表达 agent/tool graph。

适合场景：

- 如果希望 logo 更像长期品牌符号，而不是工具概念图，可以优先考虑。

## 方案 C：V4 Agent 路由选择

文件：

- `assets/brand/avatar-v4-router.svg`
- `assets/brand/avatar-v4-router-1024.png`
- `assets/brand/avatar-v4-router-460.png`
- `assets/brand/avatar-v4-router-circle-preview.png`

核心想法：中心节点向候选工具路由，并用高亮路径表达“agent 选择了一个工具”。

优点：

- 语义最贴近 “agents choose tools”。
- 比 v2 更有动作感，能表达选择、调用、路径。
- 与 org README 中关于 tool definition quality / selection problem 的叙事更贴合。

风险：

- 内部细节比 v2 多，小尺寸下箭头细节可能消失。

适合场景：

- 适合品牌说明页、README 顶部图，也适合希望更强调 agent routing 的头像。

## 方案 D：V5 CLI 调用提示符

文件：

- `assets/brand/avatar-v5-prompt.svg`
- `assets/brand/avatar-v5-prompt-1024.png`
- `assets/brand/avatar-v5-prompt-460.png`
- `assets/brand/avatar-v5-prompt-circle-preview.png`

核心想法：在括号中放入 `>_` 风格的调用提示符，强调开发者工具、终端、可执行工具链。

优点：

- 小尺寸可读性强。
- 开发者一眼能识别 CLI / command / invocation。
- 适合 MCP server、perfetto 工具、安装命令等工程语境。

风险：

- 语义偏 CLI，弱化了 AI agent / tool routing 的独特定位。
- 终端提示符在开发者品牌中较常见，差异化不如 v2/v3。

适合场景：

- 如果 Tooluse Labs 主要面向 CLI 工具、开发者安装分发、命令行工作流，可以考虑。

## 推荐排序

1. `avatar-v2.svg`：最均衡，适合作为当前 GitHub org avatar 的下一版。
2. `avatar-v3-monogram.svg`：最适合长期品牌化，适合未来做独立 favicon 或产品族标识。
3. `avatar-v4-router.svg`：概念最准确，但头像小尺寸风险略高。
4. `avatar-v5-prompt.svg`：工程感最强，但更像通用 CLI 品牌。

如果只选一个继续精修，建议选 v2。  
如果想建立更长期的品牌系统，建议在 v2 和 v3 之间做二轮对比。
