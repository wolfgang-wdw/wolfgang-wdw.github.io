---
layout: default
title:  Blog
lang: en
lang_ref: blog
permalink: "/blog/"
---
Blog Posts
<div class="post-list">
<ul>
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: site.date_format }}</span> &bull;
          <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      </li>
    {% endfor %}
</ul>
</div>
