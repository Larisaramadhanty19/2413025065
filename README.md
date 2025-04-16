<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Grafika Komputer - Larisa Ramadhanty</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f1eb;
      color: #5d4037;
      background-image: radial-gradient(circle, #d1b2a1 20%, transparent 20%), radial-gradient(circle, #d1b2a1 20%, transparent 20%);
      background-size: 30px 30px;
      background-position: 0 0, 15px 15px;
    }

    header, footer {
      background-color: #a1887f;
      color: white;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    footer {
      margin-top: 50px;
      padding: 20px;
    }

    nav {
      background-color: #d7ccc8;
      padding: 10px 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 40px;
      margin: 0;
      padding: 0;
    }

    nav ul li a {
      text-decoration: none;
      color: #4e342e;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #3e2723;
    }

    section {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }

    .kartu {
      background-color: #fefaf6;
      border-radius: 12px;
      padding: 25px;
      margin-bottom: 25px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      transition: transform 0.2s;
    }

    .kartu:hover {
      transform: translateY(-5px);
    }

    .kartu h2 {
      margin-top: 0;
      color: #5d4037;
    }

    .profil-container {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
      text-align: left;
    }

    .foto-profil {
      width: 180px;
      height: 180px;
      border-radius: 16px;
      object-fit: cover;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .profil-list {
      list-style: none;
      padding-left: 0;
    }

    .profil-list li {
      margin-bottom: 8px;
    }

    .grid-tugas {
      display: flex;
      flex-direction: column;
      gap: 20px;
      margin-top: 20px;
    }


    .tugas-item {
      background-color: #ede0d4;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }

    .tugas-item h3 {
      margin: 0 0 10px;
      color: #6d4c41;
    }

    .tugas-item a {
      text-decoration: none;
      color: #795548;
      font-weight: bold;
    }

    .tugas-item a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Grafika Komputer</h1>
    <p>Larisa Ramadhanty</p>
  </header>

  <nav>
    <ul>
      <li><a href="#profil">Profil</a></li>
      <li><a href="#tentang">Tentang</a></li>
      <li><a href="#tugas">Tugas</a></li>
    </ul>
  </nav>

  <section>
    <div class="kartu" id="profil">
      <h2>Profil</h2>
      <div class="profil-container">
        <img src="larisa.jpg" alt="Foto Larisa Ramadhanty" class="foto-profil">
        <ul class="profil-list">
          <li><strong>Nama:</strong> Larisa Ramadhanty</li>
          <li><strong>NIM:</strong> 2413025065</li>
          <li><strong>Program Studi:</strong> Pendidikan Teknologi Informasi</li>
          <li><strong>Fakultas:</strong> FKIP</li>
          <li><strong>Universitas:</strong> Universitas Lampung</li>
          <li><strong>Email:</strong> larisaramadhanty12@gmail.com</li>
          <li><strong>Domisili:</strong> Bandar Lampung, Indonesia</li>
        </ul>
      </div>
    </div>

    <div class="kartu" id="tentang">
      <h2>Tentang Saya</h2>
      <p>Halo! Saya <strong>Larisa Ramadhanty</strong>, mahasiswa semester 2 di Universitas Lampung, jurusan Pendidikan Teknologi Informasi.</p>
      <p>Saya sedang mempelajari berbagai hal seputar penerapan teknologi dalam pendidikan, termasuk materi grafika komputer seperti algoritma gambar garis dan kurva.</p>
    </div>

    <div class="kartu" id="tugas">
        <h2>Daftar Tugas Grafika Komputer</h2>
        <div class="grid-tugas">
          <div class="tugas-item">
            <h3>Tugas 1</h3>
            <p>Tokoh Perintis Grafika Komputer</p>
            <a href="https://drive.google.com/drive/folders/1Ke8DgoZhMQcrxK_0UdX7gY8tjWbX5gSq" target="_blank">Lihat Tugas</a>
          </div>
          <div class="tugas-item">
            <h3>Tugas 2</h3>
            <p>Garis DDA & Bresenham</p>
            <a href="https://drive.google.com/file/d/1c4JUQ6K8ZUu7fcrzBGT4NKU0ocVtfMlI/view?usp=drivesdk" target="_blank">Lihat Tugas</a>
          </div>
          <div class="tugas-item">
            <h3>Tugas 3</h3>
            <p>Garis Lingkaran</p>
            <a href="https://drive.google.com/file/d/1jtm9s2mWtJbqWVHXzk6Sv36cZsZTz51y/view?usp=drivesdk" target="_blank">Lihat Tugas</a>
          </div>
          <div class="tugas-item">
            <h3>Tugas 4</h3>
            <p>Pembentukan Kurva</p>
            <a href="https://drive.google.com/drive/folders/146gi-_n2utRocfQRmL9_Z9w17ysbDe_Z" target="_blank">Lihat Tugas</a>
          </div>
        </div>
      </div>
  </section>

  <footer>
    <p>&copy; 2025 Larisa Ramadhanty</p>
  </footer>

</body>
</html>
