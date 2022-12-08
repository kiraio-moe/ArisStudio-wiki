# 位置

设置文件在 `/Data/Setting.json`

# 参数

为文本可分享性，不建议使用预加载列表

- txtName 播放文件名
- auto
  - enable 启用自动播放
  - seconds 断点间间隔（秒）
- spr
  - sprPreList 人物预加载列表
- bgm
  - volume 背景音乐初始音量（0.0 ~ 1.0）
  - bgmPreList 背景音乐预加载列表
- se
  - volume 音效初始音量（0.0 ~ 1.0）
  - bgmPreList 音效预加载列表
- bg
  - bgPreList 背景图片预加载列表


# 使用例

```json
{
    "txtName": "Tutorial/T3",
    "auto": {
        "enable": false,
        "seconds": 2
    },
    "spr": {
        "sprPreList": []
    },
    "bgm": {
        "volume": 0.2,
        "bgmPreList": []
    },
    "se": {
        "volume": 1,
        "sePreList": []
    },
    "bg": {
        "bgPreList": []
    }
}
```