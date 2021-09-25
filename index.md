---
title: Cyborus
---
# Posts

{% for post in site.posts %}
  - ## [{{ post.title }}]({{ post.url }})

    {{ page.author }} - {{ page.date }}
  

{% endfor %}