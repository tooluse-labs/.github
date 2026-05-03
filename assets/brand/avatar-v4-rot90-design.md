# Tooluse Labs V4a/V4c Rotated Candidates

## V4a 与 V4c 的差别

V4a 是更简化、更粗的 router 版本。它只有一个弱化候选点、一个源点、一个被选中目标点，线条更粗、节点更大，小尺寸更稳。

V4c 保留了更明确的 “choice” 语义。左侧候选点用暗色外圈加青色内点表达未选候选，线条略细，信息量比 V4a 多一些。

## 旋转处理

这次新增两个 90 度顺时针旋转版本：

- `assets/brand/avatar-v4a-router-bold-rot90.svg`
- `assets/brand/avatar-v4c-router-choice-rot90.svg`

旋转只作用于内部三个点和连接线，外部括号、背景、安全区保持不变。旋转中心使用各自三点图形的包围盒中心。

## 初步判断

旋转后图形从 “上方源点分到左右” 变为 “左侧源点分到右上/右下”。这更像 agent 从左侧发起调用，并在右侧两个工具候选之间选择一个。

V4a rot90 更适合头像：更大、更少细节。  
V4c rot90 更适合解释概念：候选/未选关系更明显。
