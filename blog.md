# Blog posts

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.excerpt | strip_html }}</a>
  </li>
  {% endfor %}
</ul>