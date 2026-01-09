---
title: "Pertanyaan"
description: "Hantar pertanyaan atau permohonan perkhidmatan"
---

## Borang Pertanyaan

Sila isi maklumat di bawah. Semua pertanyaan akan dibalas secepat mungkin.

<form
  action="https://formspree.io/f/xgoegdgl"
  method="POST"
  enctype="multipart/form-data"
>

  <label>Nama *</label><br>
  <input type="text" name="name" required><br><br>

  <label>Nombor Telefon *</label><br>
  <input type="tel" name="phone" required><br><br>

  <label>Emel</label><br>
  <input type="email" name="email"><br><br>

  <label>Alamat Penerima</label><br>
  <textarea name="address" rows="4"></textarea><br><br>

  <label>Mesej / Maklumat Tambahan</label><br>
  <textarea name="message" rows="4"></textarea><br><br>

  <!-- Anti-spam -->
  <input type="hidden" name="_subject" value="Pertanyaan Baharu dari Laman Web">
  <input type="hidden" name="_captcha" value="false">

  <button type="submit" style="padding: 14px 28px;
 background-color: #2563eb; color: white; border: none; border-radius: 8px; font-size: 16px; font-weight: 600; cursor: pointer;">
    Hantar Pertanyaan
  </button>

</form>
