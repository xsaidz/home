---
layout: default1
title: Default
permalink: /default/
---

<h1>Selamat Datang di Situs Saya</h1>
<p>Ini adalah situs sederhana yang menggunakan tema kustom Jekyll.</p>

<section>
  <h2>Tentang Kami</h2>
  <p>Kami adalah tim yang berdedikasi dalam menyediakan konten berkualitas tinggi. Berikut adalah layanan yang kami tawarkan:</p>
  <ul>
    <li>Penulisan Konten</li>
    <li>Desain Web</li>
    <li>Konsultasi Teknologi</li>
  </ul>
</section>

<section>
  <h2>Galeri</h2>
  <div style="display: flex; gap: 10px;">
    <img src="https://via.placeholder.com/150" alt="Gambar 1" />
    <img src="https://via.placeholder.com/150" alt="Gambar 2" />
    <img src="https://via.placeholder.com/150" alt="Gambar 3" />
  </div>
</section>

<section>
  <h2>Kontak Kami</h2>
  <p>Hubungi kami melalui formulir di bawah ini untuk pertanyaan lebih lanjut:</p>
  <form action="/submit_form" method="POST">
    <label for="name">Nama:</label>
    <input type="text" id="name" name="name" required>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    
    <label for="message">Pesan:</label>
    <textarea id="message" name="message" required></textarea>
    
    <button type="submit">Kirim</button>
  </form>
</section>
 
