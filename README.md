Lab5Web.
# Login Form — HTML, CSS & JavaScript

Proyek ini adalah contoh sederhana form login yang dibuat menggunakan HTML, CSS, dan JavaScript.
Form ini menampilkan tampilan login yang responsif dan melakukan validasi input sebelum mengizinkan pengguna untuk login.

pemrogramanweb-folder/
│
├── pertemuan6.html      → Struktur utama halaman (form login)
├── style.css       → File styling untuk tampilan form

# Penjelasan Kode
1. index.html
File berisi struktur dasar halaman login.

Bagian Utama:

<form id="login">
Formulir login yang berisi input untuk username dan password.
  
  ```
  <input type="text" id="username" placeholder="Masukkan username" required>
<input type="password" id="password" placeholder="Masukkan password" required>
  ```
  
# 2. style.css
File tampilan form agar terlihat menarik dan responsif.

Gaya Utama:

Background
Menggunakan gradasi warna:
```
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

# login-container
Kotak putih di tengah halaman dengan efek bayangan, padding, dan border radius.
Input & Button Styling
Input memiliki border lembut dan efek focus biru.
Tombol login menggunakan warna ungu dengan efek hover yang sedikit lebih gelap.
