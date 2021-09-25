# Cyborus

[About me](/about.md)

## stuff
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}