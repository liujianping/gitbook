# 2.3 功能插件

这篇文章挺全的：[GitBook 插件](https://www.cnblogs.com/mingyue5826/p/10307051.html)。

加两个简单插件，修改`book.json`文件相关配置块:

````json
{
    ...
    "plugins": [
        "copy-code-button",
        "tbfed-pagefooter"
    ],
    "pluginsConfig": {
        "tbfed-pagefooter": {
            "copyright": "GitDiG.com @2019",
            "modify_label": "本文修订时间:",
            "modify_format": "YYYY-MM-DD HH:mm:ss"
        }
    }
    ...
}
````
增加新插件，需要执行插件安装命令:

````
$: gitbook install
````

再重新启动本地服务，查看效果。