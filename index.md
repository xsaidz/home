---
layout: satu
title: SaiDz.My.ID
---

<div class="row">
  <div class="container">
    
    <div class="m-2">
Halo, ini adalah halaman utama dari situs saya yang menggunakan tema default Jekyll!
    </div>
    
<div class="mx-1">
<h2> Post List</h2>
<ul class="list-unstyled">
  {% for post in site.posts %}
    <li class="mb-3">
      <h5>
        <a href="{{ post.url | relative_url }}" class="text-decoration-none">{{ post.title }}</a>
      </h5>
    </li>
  {% endfor %}
</ul>
</div>

</div>
</div>
