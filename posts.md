---
layout: default
title: Posts
permalink: /posts/
---

# Latest Posts

{% for post in site.posts limit:5 %}

## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt }}

{% endfor %}

[View all posts →]({{ '/posts/' | relative_url }})