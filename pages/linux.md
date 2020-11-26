---
layout: page
type: linux
hero_text: Linux ansible roles
permalink: /linux/
---
{% assign posts = site.posts | where:"type", "linux" %}

<ul>
{% for post in posts %}
<li>
<a href="{{ site.url }}{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
<ul>

