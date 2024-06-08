---
layout: archive
title: "Posts"
classes: wide
permalink: /posts/
author_profile: true
---

{% for post in site.posts limit: 10 %}
  {% include archive-single.html %}
{% endfor %}

<!-- {% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %} -->

{% include paginator.html %}

