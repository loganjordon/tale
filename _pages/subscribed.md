---
layout: post
title: "Subscribed!"
permalink: /subscribed
---

You've successfully subscribed to the loganjordon mailing list.

Checkout some of my most recent articles, if you haven't already:

<ul>
{% assign last_four_posts = site.posts | sort: "-date" %}
{% for post in last_four_posts limit:3 %}
	<li>
		<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
	</li>
{% endfor %}
</ul>