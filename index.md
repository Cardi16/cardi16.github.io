---
layout: Home
title: Home
---
# test

hey guys this is my homepage


# Latest Posts

{% for post in site.posts limit:5 %}

### [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt }}

{% endfor %}

[View all posts →]({{ '/posts.md/' | relative_url }})