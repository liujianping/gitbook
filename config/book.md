# 2.1 配置文件

默认情况下，初始化后的`GitBook`项目配置文件没有提供配置文件，需要进行手工创建。在项目根目录下，创建`book.json`或者名为`book.js`的配置文件。如下:

````bash
$: cat <<EOF > book.json
{
    "title": "GitBook 操作指南",
    "author": "JayL",
    "description": "GitBook 边实践边记录的结果",
    "language": "zh-Hans",
    "links": {
        "sharing": {
            "all": null,
            "facebook": null,
            "google": null,
            "twitter": null,
            "weibo": null
        },
        "sidebar": {
            "GitDiG.com": "https://gitdig.com"
        }
    },
    "styles": {},
    "plugins": [],
    "pluginsConfig": {
    }
}
EOF
````

首先增加基础项目信息。从配置可以看出，还可以进行**样式**与**功能插件**的配置。