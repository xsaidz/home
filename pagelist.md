---
layout: satu
title: PageLists
permalink: /peglis/
---

<div class="row">
  <div class="container">
<h1>Selamat Datang di Situs Saya</h1>
<p>Ini adalah situs sederhana yang menggunakan tema kustom Jekyll.</p>


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

</div>
</div>
