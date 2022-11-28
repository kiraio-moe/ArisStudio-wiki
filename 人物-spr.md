# 出现 show 
- 命令：spr show {nameId}
- 例子：spr show hihumi

# 隐藏 hide
- 命令：spr hide {nameId}
- 例子：spr hide hihumi

# 高亮 hl
- 命令：spr hl/highlight {nameId} {0.0~1.0}
- 例子：spr hl hihumi 0.5
- 0为暗，1为亮

# 设置通信效果 comm
- 命令：spr comm {nameId}
- 例子：spr comm hihumi

# 还原效果 def
- 命令：spr def {nameId}
- 例子：spr def hihumi

# 以通信效果出现 showC
- 命令：spr showC {nameId}
- 例子：spr showC hihumi

# 以通信效果消失 hideC
- 命令：spr hideC {nameId}
- 例子：spr hideC hihumi


# 面部状态 state
- 命令：spr state {nameId} {sprAnimName}
- 例子：spr state hihumi 03
- 如何查看状态名与面部表情对应关系？
  - 以 `/Data` 为根目录开启 web 服务
  - 比如用 vscode 的 Live Server 插件

# 表情 emo
- 命令：spr emo/emoticon {nameId} {emoticonName}
- 例子：spr emo hihumi Action
- emoticonName 
- 播放 `/Data/0Txt/Test/Test.txt` 查看

# 动画还原 animInit 
- 命令：spr animInit {nameId}
- 例子：spr animInit hihumi

# 倒地动画 down
- 命令：spr down {nameId}
- 例子：spr down hihumi

# 升起动画 up
- 命令：spr up {nameId}
- 例子：spr up hihumi

# 设置横坐标位置 x
- 命令：spr x {nameId} {x}
- 例子：spr x hihumi -5
- 建议位置 [-10,-5,0,5,10]

# 移动到指定位置 move
- 命令：spr move {nameId} {x}
- 例子：spr move hihumi 5

# 人物靠近 close
- 命令：spr close {nameId}
- 例子：spr close hihumi

# 人物后退 back
- 命令：spr back {nameId}
- 例子：spr back hihumi

# 预设抖动效果 preShake
- 目前没做这部分

# 自定义x轴抖动 shakeX
- 命令：spr shakeX {nameId} {speed} {amplitude} {period}
- 例子：spr shakeX hihumi 20 1 6

# 自定义y轴抖动 shakeY
- 命令：spr shakeY {nameId} {speed} {amplitude} {period}
- 例子：spr shakeY hihumi 8 -1 3