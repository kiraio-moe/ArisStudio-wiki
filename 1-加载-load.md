> 加载前请确定素材文件放在[相应文件夹](https://github.com/Tualin14/ArisStudio/wiki#%E6%96%87%E4%BB%B6%E7%9B%AE%E5%BD%95%E7%BB%93%E6%9E%84)中

# 人物加载

- 命令 `load spr {nameId} {sprName}`
- 例 `load spr midori midori_spr`

## 以通信状态加载

- 命令 `load sprC {nameId} {sprName}`
- 例 `load sprC midoriC midori_spr`
- 通信状态加载的学生可以用 `spr` 命令使用

## 加载(或以通信状态加载) spine 制作自定义角色

- 命令 `load custom/customC {nameId} {scale} {idle} {customName} [imglist]`
- 例 `load custom h 1 Idle_01 hihumi_spr [hihumi_spr.png]`
- `customName` 用来识别 `atlas` 与 `skel`，`imgList` 识别图片

## 加载(或以通信状态加载)以图片实现差分的自定义角色

> 参考 1000x1200，scale 2.7

- 命令 `load char/charC {nameId} {scale} {charFolder} [imglist]`
- 例 `load char/charC tt 2 test [01.png, 02.png,  03.png, 04.png]`
- 请以文件夹区分人物，如
  - Character
    - test
      - 01.png
      - 02.png
      - 03.png
      - 04.png

# 背景加载

- 命令 `load bg {nameId} {bgName}`
- 例 `load bg GameDevRoom_Night BG_GameDevRoom_Night.jpg`

# 覆盖图片加载

- 命令 `load cover {nameId} {coverName}`
- 例 `load cover Player popup02.png`

# 背景音乐加载

- 命令 `load bgm {nameId} {bgmName}`
- 例 `load bgm Theme_64 Theme_64.ogg`

# 音效加载

- 命令 `load se {nameId} {seName}`
- 例 `load se Granted SE_Granted_01.wav`

# 结束加载

- 命令 `load end`
- 例 `load end`
- 此命令必须存在于加载结束后
