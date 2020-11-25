---
layout: page
title: Windows
permalink: /windows/
---
{% assign posts = site.posts | where:"type", "windows" %}

<ul>
{% for post in posts %}
<li>
<a href="{{ site.url }}{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
<ul>
