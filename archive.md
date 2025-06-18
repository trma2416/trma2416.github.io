---
layout: page
title: Blog Posts
---

{% for tag in site.tags %}
  {% assign tag_name = tag[0] %}
  <h3>{{ tag_name | default: "Untagged" }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
