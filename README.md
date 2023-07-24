# 静态网址导航
适合各人员配置
```json
[
    {
        "id": "常用推荐",                          //必填，菜单列表与展示内容时跳转
        "info": [
            {
                "url": "https://www.baidu.com",
                "name": "百度",                   // 标题
                "desc": "百度一下，你就知道",      // 导航的描述
                "logo": ""                       // logo不填时默认取网站的icon
            },
            {
                "url": "https://www.github.com",
                "name": "github",
                "desc": "github",
                "logo": "./assets/images/default.png"     //本地图片放在assets/images目录中
            }
        ]
    },
    {
        "id": "学习资源"
    },
    {
        "id": "常用工具"
    },
    {
        "id": "社区资讯"
    }
]

```
