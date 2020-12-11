---
layout: default
title: "Jim Kosem: Design, strategy & research"
---

### Hi, I'm Jim.

## I work across design, research and strategy to make emerging technologies practical realities.

I work on products and services with impact and scale like government, a fairer and more secure peer-to-peer internet to reinventing what used to be email.

I design. Sometimes that's an interface. Sometimes it's lots of screens. Sometimes it's extensive maps and documentation. It’s all design. Just like researching who might be using the wider service in which that sits, whether it be on a London housing estate or a village in Rwanda. Likewise, that means developing the strategy of a product or service, because that is helping find out what to design.

Design should be a very broad practice, calling upon all the ways we can think of and use to solve our world's problems. Sometime a well written sentence can do the job of an entire application and sometimes you need to work at what not to design.

<h4>What I'm up to lately</h4>
<ul class="myposts">
{% for post in site.categories.update limit:3 %}
    <li><a href="{{ post.url }}">{{ post.title}}</a>
    <span class="postDate">{{ post.date | date: "(%-d %b %Y)" }}</span>
    </li>
{% endfor %}
</ul>
