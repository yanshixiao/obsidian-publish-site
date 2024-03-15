---
share: true
title: Home
sharetitle: index
---

[网站收集](./2024-03-15-%E7%BD%91%E7%AB%99%E6%94%B6%E9%9B%86.md#)



欢迎！
<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
