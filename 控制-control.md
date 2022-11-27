# 键盘控制

- F 全屏切换
- R 分辨率切换
- 1，2，3 自上到下 选择按钮
- Space 点击

# 设置部分 setting.json

- txtName 播放脚本名称
- auto
  - 启用自动
  - 进行下一个行为间隔时间
- spr 
  - sprPreList 人物预加载

示例：
```json
{
    "txtName": "播放",
    "auto": {
        "enable": true,
        "seconds": 1.5
    },
    "spr": {
        "sprPreList": [
            {
                "nameId": "midori",
                "sprName": "midori_spr"
            },
            {
                "nameId": "momoi",
                "sprName": "momoi_spr"
            }
        ]
    }
}
```