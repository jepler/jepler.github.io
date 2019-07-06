---
layout: default
title: Jeff Epler, Freelance Software Developer
---
About Jeff
==========

I've been a software developer ever since I first started typing in program listings on an 80s home computer.

I'm available for contract-based software development, with an emphasis on embedded and linux software.

I've been a contributor to Free and Open Source software for over 20 years.
See my [github profile](https://github.com/jepler) for my contributions and original software.


My Blog
=======

I've chosen these posts with a technical emphasis from my personal blog:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
