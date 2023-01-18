# 显示

- 出现 `spr show {nameId}`
- 隐藏 `spr hide {nameId}`
- 直接出现 `spr showD {nameId}`
- 直接隐藏 `spr hideD {nameId}`
- 高亮 `spr hl/highlight {nameId} {0.0~1.0}` (0 为暗，1 为亮,建议 0.5 和 1)

# 面部状态

- 命令：`spr state {nameId} {stateId}`
- 例子：`spr state hihumi 03`
- [state 预览方法](./9-state%E9%A2%84%E8%A7%88%E6%96%B9%E6%B3%95-state_previe)

# emo 表情

- 命令：`spr emo/emoticon {nameId} {emoName}`
- 例子：`spr emo hihumi Action`
- [emo 表情预览](./9-emo%E8%A1%A8%E6%83%85%E9%A2%84%E8%A7%88-emo_preview)

# 动画

- 倒地动画 `spr down {nameId}`
- 升起动画 `spr up {nameId}`
- 设置空动画，用来还原动画状态 `spr empty {nameID}`

# 位置

- 设置 X 轴位置 `spr x {nameID} {x}` (建议-10，-5，0，5，10)
- 以 speed 速度延 X 轴移动到某位置 `spr moveX/move {nameID} {x} {speed}`
- 设置 Y 轴位置 `spr y {nameID} {y}`
- 以 speed 速度延 X 轴移动到某位置 `spr moveY {nameID} {y} {speed}`
- 人物靠近 `spr close {nameID}`
- 人物后退 `spr back {nameId}`
- X/Y 轴抖动 `spr shakeX/shakeY {nameId} {speed} {amplitude} {period}`
- 更改图层，调换覆盖顺序 `spr z {nameID} {z}` (默认都在 0 层，先加载在前面，1 ~ 5 可用)
