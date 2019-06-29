---
contentTitle: Yazılar
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2>
        <a href="{{ post.url | absolute_url }}">{{ post.title }}</a>
      </h2>
      <p><i>{{ post.subtitle }}</i></p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
