---
title: Home
permalink: /
---
# from his eminence's desk

hey guys this is my homepage if you're seeing this it should've loaded......

<center>
<img src="{{ '/assets/mzsa.gif' | relative_url }}">
</center>

<div class="dotted_line"></div>
# Latest Posts

{% for post in site.posts limit:5 %}

### [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt }}

{% endfor %}

[View all posts →]({{ '/posts.md/' | relative_url }})