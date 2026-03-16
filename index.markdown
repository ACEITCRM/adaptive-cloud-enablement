---
layout: default
title: Home
---

## Latest Posts

<ul>
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url | relative_url }}">{{ post.title }}</a>
			<small>— {{ post.date | date: "%b %-d, %Y" }}</small>
		</li>
	{% endfor %}
</ul>

## Pages

- [About]({{ "/about/" | relative_url }})
- [Nate Herndon Bio]({{ "/about/nate-herndon" | relative_url }})
