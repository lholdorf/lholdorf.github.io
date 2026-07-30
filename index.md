---
layout: home
title: Let me think about it
pagination:
  enabled: true
---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}
