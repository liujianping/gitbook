# 2.2 主题样式

`GitBook`默认的主题样式已经非常好了，如果需要进行微调的化，可以增加样式表对指定样式进行覆盖。（不是专业前端，这么理解吧）。

可以进行调整的样式分别是以下几种模式下的样式，以下参考配置项：

````json
{
    ...
    "styles": {
        "website": "styles/website.css",
        "ebook": "styles/ebook.css",
        "pdf": "styles/pdf.css",
        "mobi": "styles/mobi.css",
        "epub": "styles/epub.css"
    },
    ...
}
````
当然这些配置，如上配置的话，需要在项目目录中创建相应的样式文件，并定义相应的样式。以`website`样式为例：

````
$: mkdir styles
$: cat <<EOF > styles/website.css
h1 , h2{
    border-bottom: 1px solid #EFEAEA;
}
EOF
````
给标签`<h1>`,`<h2>`增加下划线样式。