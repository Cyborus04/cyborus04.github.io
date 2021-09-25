---
title: Cyborus
---
# Posts

{% for post in site.posts %}
  - ## [{{ post.title }}]({{ post.url }})
    <small>{{ page.author }} - {{ page.date }}</small>


{% endfor %}