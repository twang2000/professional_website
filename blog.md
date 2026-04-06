---
layout: page
title: Blog
permalink: /blog/
---

Implementation notes, testing strategies, and engineering postmortems.

{% if site.posts.size > 0 %}
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%B %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
{% else %}
_No posts yet. Check back soon._
{% endif %}
