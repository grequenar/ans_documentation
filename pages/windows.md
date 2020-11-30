---
layout: default
type: windows
permalink: /windows/
---
{% assign posts = site.posts | where:"type", "windows" %}

{% for post in posts %}
<li>
<span class="post-meta">{{ post.date }}</span>
<h3>
<a class="post-link" href="{{ site.url }}{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
</h3>
</li>
{% endfor %}
