---
layout: default
title: "Jim Kosem: Design, strategy & research"
---

# Blog

Here is the blog where updates will go. There may be some better sorting at some point or images or something.

<ul class="bloglist">
  {% for post in site.posts %}
    <li>

      <!-- <a href="{{ post.url }}">{{ post.title }}</a> -->

      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="date">{{ post.date | date: "(%-d %B %Y)"  }}</span>

    </li>
  {% endfor %}
</ul>

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
