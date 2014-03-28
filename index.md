---
layout: page
title: Joez Blog's
tagline: Supporting tagline
---
{% include JB/setup %}

阅读 [Jekyll Quick Start文档](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

完整 Jekyll Bootstrap 文档: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## 更新Jekyll Blog属性

在 `_config.yml` 修改自己的Blog数据属性:
    
    title : My Blog =)
    
    author :
      name : username
      email : admin@local
      github : username
      twitter : #

The theme should reference these variables whenever needed.
    
## 示例文章

此文件为例示文章，帮助搭建Blog数据.
当你不需要的时候，可以直接删除 `_posts/core-samples` 文件夹.

    $ rm -rf _posts/core-samples

以下是样本 "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 待办事项

这个主题仍然是未完成的。如果您想添加为一个贡献者, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
我们需要清理的主题，使主题具有特定标记的例子主题的使用指南。

