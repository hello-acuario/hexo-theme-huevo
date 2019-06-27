# hexo-theme-huevo
这是一个自用 hexo 主题，这里有我的博客的链接，还有截图。

[Junso's Huevo](http://www.baidu.com)

## 使用事项:
### 全局_config.yml：
关闭默认代码高亮功能以使用hight.js
```yml
highlight:
  enable: false
  line_number: false
  auto_detect: false
  tab_replace:
```

使用搜索功能
···yml
search:
  path: search.json
  field: post
  content: true
···

使用rss
···yml
feed:
    type: atom
    path: rss.xml
    limit: 20
···

### 主题下目录surce/js/comment.js
修改gitalk配置信息

### 写作相关
1. 请务必为每篇文章设置预览片段即在一段内容后加上
```html
<!-- more -->
```
这样只会文章页主要部分只会渲染改标记之后的，之前的会渲染在文章列表的预览部分以及文章页的header部分


2. 可以为每篇文章加上description属性以显示文章短简介
