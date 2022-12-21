# 文件位置

设置文件在 `/Data/Setting.json`

# 参数


- txtName 播放文件名
- auto
  - enable 启用自动播放
  - seconds 断点间间隔（秒）
- bgm
  - volume 背景音乐初始音量（0.0 ~ 1.0）
- se
  - volume 音效初始音量（0.0 ~ 1.0）

# 使用例

```json
{
    "txtName": "Demo",
    "auto": {
        "enable": false,
        "seconds": 2
    },
    "bgm": {
        "volume": 0.2
    },
    "se": {
        "volume": 1
    }
}```
