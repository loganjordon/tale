---
layout: post
title: "Archive"
permalink: /archive
---

A list of every article on the site:
{% assign posts = site.posts | sort: '-date' %}
{% for post in posts %}
  {% include post-list-item.html %}
{% endfor %}