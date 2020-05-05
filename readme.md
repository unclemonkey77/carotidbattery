<ul>
  {% for post in site.posts %}
    <li>
      <a href="/carotidbattery{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
