---
title:  "Cyborus"
---

# Cyborus

[About me](/about.md)

## stuff
<ol>
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ol>