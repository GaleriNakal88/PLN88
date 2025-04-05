<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Marketplace terpercaya dengan produk berkualitas dan artikel informatif.">
  <meta name="keywords" content="marketplace, produk murah, belanja online, promo, artikel produk">
  <meta name="author" content="Nama Toko Kamu">
  <title>Marketplace Landing Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<style>
  body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

.header {
  padding: 10px 0;
  background: #f5f5f5;
  text-align: center;
}

.logo {
  height: 50px;
}

.banner-img {
  width: 100%;
  height: auto;
}

.produk-section {
  padding: 40px 0;
  background-color: #fefefe;
}

.produk-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.produk-card {
  flex: 1 1 calc(33.333% - 20px);
  background: #fff;
  border: 1px solid #ddd;
  padding: 15px;
  border-radius: 10px;
}

.harga {
  font-weight: bold;
  color: #e91e63;
}

.artikel {
  padding: 40px 0;
  background: #fafafa;
}

.artikel article {
  margin-bottom: 20px;
}

.footer {
  background: #222;
  color: #fff;
  padding: 30px 0;
}

.footer-info,
.footer-legal {
  margin-bottom: 15px;
}

.footer a {
  color: #fff;
  text-decoration: underline;
}

</style>
<body>
  <!-- LOGO -->
  <header class="header">
    <div class="container">
      <img src="logo.png" alt="Logo Marketplace" class="logo">
    </div>
  </header>

  <!-- BANNER -->
  <section class="banner">
    <img src="banner.jpg" alt="Promo Banner" class="banner-img">
  </section>

  <!-- PRODUK -->
  <section class="produk-section">
    <div class="container">
      <h2>Produk Unggulan</h2>
      <div class="produk-grid">
        <div class="produk-card">
          <h3>Nama Barang 1</h3>
          <p class="harga">Rp 100.000</p>
          <p class="deskripsi">Deskripsi singkat produk yang menarik dan SEO-friendly.</p>
        </div>
        <div class="produk-card">
          <h3>Nama Barang 2</h3>
          <p class="harga">Rp 150.000</p>
          <p class="deskripsi">Deskripsi singkat produk yang menarik dan SEO-friendly.</p>
        </div>
        <!-- Tambah produk lain di sini -->
      </div>
    </div>
  </section>

  <!-- ARTIKEL -->
  <section class="artikel">
    <div class="container">
      <h2>Artikel Terkait</h2>
      <article>
        <h3>Cara Memilih Produk Berkualitas di Marketplace</h3>
        <p>Memilih produk terbaik di marketplace memerlukan ketelitian. Pastikan membaca deskripsi, ulasan pengguna, dan melihat reputasi penjual sebelum membeli...</p>
        <a href="#">Baca Selengkapnya</a>
      </article>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    <div class="container">
      <div class="footer-info">
        <p><strong>Alamat Toko:</strong></p>
        <p>Jl. Contoh No.123, Jakarta, Indonesia</p>
        <div class="maps">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!..." width="100%" height="200" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
      </div>
      <div class="footer-legal">
        <a href="#">Privacy Policy</a> |
        <a href="#">Syarat & Ketentuan</a>
      </div>
      <p>&copy; 2025 Nama Toko Kamu. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>

