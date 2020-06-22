<ul>
  {% for post in site.posts %}
    <li>
      <a href="blog{{ post.url }}">{{ post.title }}</a> {{ post.url }}
    </li>
  {% endfor %}
</ul>
