<ul>
  {% for post in site.posts %}
    <li>
      <a href="blog{{ post.url }}">{{ post.title,url }}</a>
    </li>
  {% endfor %}
</ul>
