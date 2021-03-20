---
layout: default
---

<div id="home">
  <ul class="posts">
    {% for post in site.posts %}
      <li>
        <a href="{{ site.baseurl }}{{ post.permalink }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</div>
