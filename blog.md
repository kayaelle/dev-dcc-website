---
layout: default
title: Blog
---

Learn more about the DCC and our work.


{% for post in site.posts %}
  <p>
    <h6><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - {{ post.author }} - {{ post.date | date: "%b %d, %Y"}}</h6>
  </p>
{% endfor %}

