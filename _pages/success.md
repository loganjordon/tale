---
layout: post
title: "Message Sent!"
permalink: /success
---

Your message was successfully sent. If you asked for a reply, expect one in your inbox in less than 24 hours.

In the meantime, checkout some of my most recent articles:

<ul>
{% assign last_four_posts = site.posts | sort: "-date" %}
{% for post in last_four_posts limit:3 %}
	<li>
		<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
	</li>
{% endfor %}
</ul>