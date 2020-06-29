# 操作指南

本书是一本`GitBook`功能的实践项目，方便测试相关功能与插件。项目完全开源，需要请自取。

## 工具安装

````bash
$: npm i gitbook-cli -g
````

## 快速开始

````bash
# 样例项目
$: mkdir sample; cd sample
# 初始化目录
$: gitbook init
# 安装依赖
$: gitbook install
# 本地服务
$: gitbook serve
# 打包
$: gitbook build . docs
````

## 项目下载

本项目地址: [github.com/liujianping/gitbook](github.com/liujianping/gitbook).可直接下载测试。

````
$: git clone https://github.com/liujianping/gitbook.git
$: cd guide
$: gitbook install
$: gitbook serve
````

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>
<script>
  var gitalk = new Gitalk({
      clientID: '381ef6e29bdffb9ad797',
      clientSecret: '558305235c247d8766aa9d051cfce259818c0b85',
      repo: 'website',
      owner: 'gitdigg',
      admin: ['liujianping'],
      id: location.pathname,      // Ensure uniqueness and length less than 50
      distractionFreeMode: false  // Facebook-like distraction free mode
    })
    gitalk.render('gitalk-container')
</script>

