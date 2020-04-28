# Hello World

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {% raw %}
      {{ post.excerpt }}
      {% endraw %}
    </li>
  {% endfor %}
</ul>