---
permalink: /post/
title: "Post"
excerpt: "post.md"
last_modified_at: 2018-07-01T12:04:24-04:00
toc: true
tags: [Post]
---
<ul>
    {% for post in site.posts %}
      {post}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
</ul>
hello