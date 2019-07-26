---
layout: page
title : Articles
header : Post Archive
group: navigation
---
{% include JB/setup %}

## Articles

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>