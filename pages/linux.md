---
layout: page
type: linux
hero_text: Linux ansible roles
permalink: /linux/
---
{% assign posts = site.posts | where:"type", "linux" %}

{% for post in posts %}
<li>
<span class="post-meta">Nov 27, 2020</span>
<h3>
<a class="post-link" href="{{ site.url }}{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
</h3>
</li>
{% endfor %}


