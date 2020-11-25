---
layout: page
title: Linux
permalink: linux.html
---
{% assign posts = site.posts | where:"type", "linux" %}

<ul>
{% for post in posts %}
<li>
<a href="{{ site.url }}{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
<ul>
