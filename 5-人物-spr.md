# 基础

- 出现 `spr show {nameId}`
- 隐藏 `spr hide {nameId}`
- 直接出现 `spr showD {nameId}`
- 直接隐藏 `spr hideD {nameId}`
- 高亮 `spr hl/highlight {nameId} {0.0~1.0}` (0为暗，1为亮,建议0.5和1就行)

# 通信效果

- 设置通信效果 `spr comm/communication {nameId}`
- 还原效果 `spr def/default {nameId}`
- 以通信效果出现 `spr showC {nameId}`
- 以通信效果消失 `spr hideC {nameId}`
- 在通信效果时，如果使用 state 改面部表情会取消掉通信状态，如需要通信状态修改表情，[请以通信状态加载](https://github.com/Tualin14/baPlayer/wiki/1-%E5%8A%A0%E8%BD%BD-load#%E4%BB%A5%E9%80%9A%E4%BF%A1%E7%8A%B6%E6%80%81%E5%8A%A0%E8%BD%BD)

# 面部状态

- 命令：`spr state {nameId} {stateId}`
- 例子：spr state hihumi 03
- [如何查看状态名与面部表情对应关系?](/Tualin14/baPlayer/blob/main/Doc/preview_state.md)

# 表情

- 命令：`spr emo/emoticon {nameId} {emoName}`
- 例子：`spr emo hihumi Action`
- [emoName preview](/Tualin14/baPlayer/blob/main/Doc/preview_emo.md)

# 动画

- 倒地动画 `spr down {nameId}`
- 升起动画 `spr up {nameId}`
- 设置空动画，用来还原动画状态 `spr empty {nameID}`

# 位置

- 设置水平位置 `spr x {nameID} {x}` (建议-10，-5，0，5，10)
- 是以speed速度移动到某位置 `spr move {nameID} {x} {speed}`
- 人物靠近 `spr close {nameID}`
- 人物后退 `spr back {nameId}`
- X/Y轴抖动 `spr shakeX/shakeY {nameId} {speed} {amplitude} {period}`
- 更改图层，调换覆盖顺序 `spr z {z}`