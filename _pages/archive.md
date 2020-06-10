---
layout: post
title: "Archive"
permalink: /archive
---

A list of every article on the site:
{% for post in site.posts %}
  {% include post-list-item.html %}
{% endfor %}