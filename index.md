---
layout: home
title: SaiDz.My.ID
---

Halo, ini adalah halaman utama dari situs saya yang menggunakan tema default Jekyll!

<h2>Daftar Post</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%d %B %Y" }}
    </li>
  {% endfor %}
</ul>

<h2>Daftar Halaman</h2>
<ul>
  {% for page in site.pages %}
    {% if page.title and page.title != "Home" %} <!-- Optional: skip halaman beranda -->
      <li>
        <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
