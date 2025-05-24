# PerancanganWeb-DesainGrafis-BisDignomor3

Struktur dasar HTML5 dirancang untuk semantik yang lebih baik, sehingga lebih mudah dipahami oleh browser, mesin pencari, dan pengembang. Untuk halaman profil, struktur HTML5 yang baik sebaiknya mencakup elemen-elemen seperti <header>, <main>, <section>, dan <footer>.

Berikut adalah penjelasan dan contoh kode HTML5 untuk halaman profil sederhana:

Penjelasan Struktur Dasar HTML5
Elemen	Fungsi
<header>	Biasanya berisi judul halaman, logo, atau navigasi utama.
<main>	Bagian utama isi halaman, hanya boleh satu <main> per halaman.
<section>	Digunakan untuk membagi konten dalam grup semantik (misalnya: tentang, kontak, dll).
<footer>	Bagian bawah halaman. Berisi info tambahan seperti copyright.

Contoh Kode HTML5 Halaman Profil
html
Salin
Edit
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Profil Saya</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header, footer {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    main {
      padding: 20px;
    }
    section {
      margin-bottom: 30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Profil Muhamad Reza</h1>
    <p>Account Manager - Lion Parcel</p>
  </header>

  <main>
    <section id="tentang">
      <h2>Tentang Saya</h2>
      <p>Saya adalah Account Manager berpengalaman di bidang logistik dan e-commerce. Saat ini saya bekerja di Lion Parcel, fokus pada pengembangan bisnis corporate.</p>
    </section>

    <section id="pengalaman">
      <h2>Pengalaman Kerja</h2>
      <ul>
        <li>Lion Parcel (2021 - sekarang)</li>
        <li>JNE Express (2018 - 2021)</li>
      </ul>
    </section>

    <section id="kontak">
      <h2>Kontak</h2>
      <p>Email: reza@example.com</p>
      <p>Telepon: 0812-3456-7890</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Muhamad Reza. Semua hak dilindungi.</p>
  </footer>

</body>
</html>
Catatan Tambahan
Gunakan elemen <article> jika bagian dalam <section> adalah konten mandiri (misalnya: postingan blog).

Bisa ditambahkan <nav> jika ingin membuat navigasi halaman.

Untuk keperluan SEO dan aksesibilitas, pastikan menggunakan heading (<h1>–<h6>) secara hierarkis.
