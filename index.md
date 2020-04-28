# Hello World

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {% include {{ post.url }} %}
    </li>
  {% endfor %}
</ul>