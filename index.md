---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h2>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
        <span class="post-meta" style = "font-size:8pt">{{ post.date | date: "%b %-d, %Y" }}</span>
      </h2>

    </li>
  {% endfor %}
</ul>
