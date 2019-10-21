---
title: Bedework Calendar
menutitle: Home
layout: default
---

Bedework is an *open-source enterprise calendar system* that supports public, personal, and group calendaring.
It is designed to conform to current calendaring standards with a goal of attaining strong interoperability
between other calendaring systems and clients. Bedework is built with an emphasis on higher education, though
it can be (and is) used by many commercial enterprises.

You may choose to deploy Bedework for public events calendaring, personal calendaring and
scheduling, or both. Bedework is built in Java and is suitable for embedding in other applications or in
portals and has been deployed across a wide range of environments.

## Recent News

<ul>
  {% for post in site.posts limit:1 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>