# Tooluse Labs V4 Iterations

## 目标

V4 的核心概念是 “agent 在候选工具中选择并调用一个工具”。这次优化不改变大方向，只针对 GitHub 头像场景做小尺寸可读性增强。

主要改动原则：

- 强化被选中的路径。
- 减少空心节点、箭头、分支等细节对小尺寸的干扰。
- 保留青色代码括号，确保仍属于同一品牌系统。
- 保留深色底和琥珀色选择焦点。

## 候选版本

### V4a：Bold Router

文件：

- `assets/brand/avatar-v4a-router-bold.svg`
- `assets/brand/avatar-v4a-router-bold-1024.png`
- `assets/brand/avatar-v4a-router-bold-460.png`
- `assets/brand/avatar-v4a-router-bold-circle-preview.png`

特点：

- 最接近原 V4，但放大节点并加粗高亮路径。
- 删除箭头细节，让小尺寸只读“一个源节点选择一个目标工具”。
- 左侧候选工具保留为弱化分支。

判断：

- 这是最稳的 V4 优化版，适合直接作为 GitHub org avatar 候选。

### V4b：Route Arrow

文件：

- `assets/brand/avatar-v4b-router-arrow.svg`
- `assets/brand/avatar-v4b-router-arrow-1024.png`
- `assets/brand/avatar-v4b-router-arrow-460.png`
- `assets/brand/avatar-v4b-router-arrow-circle-preview.png`

特点：

- 强调“调用动作”，从源节点指向被选工具。
- 比 V4a 更有方向性。

判断：

- 概念清楚，但箭头在小尺寸下可能变成一团高亮笔画。

### V4c：Route Choice

文件：

- `assets/brand/avatar-v4c-router-choice.svg`
- `assets/brand/avatar-v4c-router-choice-1024.png`
- `assets/brand/avatar-v4c-router-choice-460.png`
- `assets/brand/avatar-v4c-router-choice-circle-preview.png`

特点：

- 保留“候选工具 + 被选路径”的语义。
- 左侧候选节点从空心改成更稳的实心/内点结构。

判断：

- 比原 V4 稳，但仍有两条路线，复杂度略高于 V4a。

### V4d：Selected Route Check

文件：

- `assets/brand/avatar-v4d-router-check.svg`
- `assets/brand/avatar-v4d-router-check-1024.png`
- `assets/brand/avatar-v4d-router-check-460.png`
- `assets/brand/avatar-v4d-router-check-circle-preview.png`

特点：

- 把“选中路径”抽象成近似 check 的紧凑路由。
- 小尺寸最强，图形最干净。

判断：

- 视觉上很稳，但语义会偏向“完成/验证”，弱化了 agent routing 的业务含义。

## 推荐

如果只在 V4 系列中选择，推荐顺序：

1. `avatar-v4a-router-bold.svg`：最均衡，保留 V4 语义并提升小尺寸稳定性。
2. `avatar-v4c-router-choice.svg`：语义更完整，但视觉复杂度略高。
3. `avatar-v4b-router-arrow.svg`：动作感强，但小尺寸风险更高。
4. `avatar-v4d-router-check.svg`：最清楚，但容易被理解成完成状态。

建议下一步优先精修 V4a。
