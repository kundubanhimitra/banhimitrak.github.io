---
layout: page
title: Blog Archive
---

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <!--<li><a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a></li>-->
   <li> <a href="https://kundubanhimitra.github.io/banhimitrak.github.io/2021/03/08/blog-post-title-from-file-name.html">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a><li>
    {% endfor %}
  </ul>
{% endfor %}
