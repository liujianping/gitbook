# 评论: gitalk 

此页留给大家评论，顺便测试`gitalk`的功能。直接再需要提供评论的内容中增加以下代码:

````markdown
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>
<script>
  var gitalk = new Gitalk({
      clientID: 'YOUR clientID',
      clientSecret: 'YOUR clientSecret',
      repo: 'YOUR repo',
      owner: 'YOUR owner',
      admin: ['YOUR admin'],
      id: location.pathname,      // Ensure uniqueness and length less than 50
      distractionFreeMode: false  // Facebook-like distraction free mode
    })
    gitalk.render('gitalk-container')
</script>
````

## 评论区

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

