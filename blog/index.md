---
layout: page
title: Blog
---

<!-- permalink: /blog/blog -->

<div class="posts">
{% for post in site.posts %}
  <article class="post">
   <h1><a   href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
  </article>
{% endfor %}
</div> 




