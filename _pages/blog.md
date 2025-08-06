---
layout: page
title: Blog
permalink: /blog/
---

# Roofing Advice & Tips

Welcome to the Royal Roofing blog — your source for roofing tips, seasonal advice, and maintenance checklists for homes across Cornwall.

---

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt | strip_html | truncate: 160 }}
<p><a href="{{ post.url }}">Read more →</a></p>
---
{% endfor %}
