---
layout: default
title: Articles
permalink: /articles/
---
<link rel="icon" href="images/lopos_icon.ico" type="image/x-icon">
<h1>
  Articles
</h1>

{% for post in site.posts %}
<article class="blog-item">
  <h2>
    <a href="{{post.url | relative_url}}"> {{ post.title }} </a>
  </h2>

  <a href="{{post.url | relative_url}}"> Lire l'article ➞ </a>
</article>
<hr />
{% endfor %}
