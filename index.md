---
title: Home
permalink: /
---
# encyclical from his eminence's desk

hi!! this is my professional website. yes i know it looks like a mess right now i've been working on fixing all the links. if something's egregiously wrong, do let me know via any contact method that you know you can reach me at :) ciao!

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
