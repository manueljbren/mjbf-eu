---
layout: default
title: "Posts about PIL"
abstract: "Thoughts and reflections born while I study or research. Zero AI. You can also find me on <a href='https://orcid.org/0009-0007-3934-8994' target='_blank' rel='noopener noreferrer'>ORCID</a>, <a href='https://dialnet.unirioja.es/servlet/autor?codigo=7231187' target='_blank' rel='noopener noreferrer'>Dialnet</a> or <a href='https://linkedin.com/in/manueljbren' target='_blank' rel='noopener noreferrer'>LinkedIn</a>."
---

<ul class="posts-flex">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="post-meta">{{ post.date | date: "%b %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
EOF