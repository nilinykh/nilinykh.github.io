---
layout: page
title: Blog
---

Just some random thoughts.
All posts can be found here:

  <div style="font-size:0.8rem">
    <ul>
      {% for post in paginator.posts %}
        <li>
          <a href="{{ post.url }}">{{ post.date | date_to_string }} &middot; {{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
  </div>