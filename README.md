
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profile Saya</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body, html { height: 100%; font-family: Arial, sans-serif; color: #333; scroll-behavior: smooth; }

    /* Background gradasi soft abu-abu dengan animasi */
    body {
      background: linear-gradient(135deg, #f0f0f0, #d6d6d6, #cfcfcf);
      background-size: 400% 400%;
      animation: gradientMove 12s ease infinite;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header, footer {
      background: rgba(51,51,51,0.9);
      text-align: center;
      padding: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.5);
    }

    header h1 {
      font-size: 2rem;
      color: #ddd;
      margin-bottom: 0.5rem;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    nav ul li a {
      text-decoration: none;
      color: #f0f0f0;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #00ffcc;
    }

    section {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 2rem;
    }

    #home, #tentang, #kontak, #pengalaman {
      background: rgba(128,128,128,0.6);
      margin: 2rem;
      border-radius: 15px;
      padding: 2rem;
      backdrop-filter: blur(6px);
      box-shadow: 0 4px 20px rgba(0,0,0,0.4);
      text-align: center;
     
    }

    section h2 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      color: #222;
    }

    section p {
      font-size: 1rem;
      line-height: 1.6;
      max-width: 600px;
      text-align: center;
      color: #444;
      margin-top: 1rem;
    }

    section img {
      max-width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.3);
      margin-bottom: 1rem;
    }

    footer p {
      color: #aaa;
      font-size: 0.9rem;
    }
  </style>
</head>
<style>
  /* ... kode CSS kamu yang lama ... */

  footer p {
    color: #aaa;
    font-size: 0.9rem;
  }

  /* === PITA HITAM UNTUK KOLOM PENGALAMAN ORGANISASI === */
  #pengalaman {
    position: relative;
    overflow: hidden;
  }

  #pengalaman::before {
    content: "she";
    position: absolute;
    top: 15px;
    left: -60px;
    width: 200px;
    height: 40px;
    background: black;
    color: white;
    text-align: center;
    line-height: 40px;
    font-weight: bold;
    transform: rotate(-45deg);
    box-shadow: 0 2px 6px rgba(0,0,0,0.5);
  }
  <style>
  /* ... kode CSS kamu yang lama ... */

  footer p {
    color: #aaa;
    font-size: 0.9rem;
  }

  /* === PITA HITAM UNTUK KOLOM TENTANG SAYA === */
  #tentang {
    position: relative;
    overflow: hidden;
  }

  #tentang::before {
    content: "star";
    position: absolute;
    top: 15px;
    left: -60px;
    width: 200px;
    height: 40px;
    background: black;
    color: white;
    text-align: center;
    line-height: 40px;
    font-weight: bold;
    transform: rotate(-45deg);
    box-shadow: 0 2px 6px rgba(0,0,0,0.5);
  }
</style>



<body>
  <header>
    <h1>Profil Saya</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#tentang">Tentang</a></li>
        <li><a href="#kontak">Kontak</a></li>
        <li><a href="#pengalaman">Pengalaman Organisasi</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h2> Lidya Star She Tobing</h2>
    <!-- Foto profil yang baru diunggah -->
    <img src="https://uploads.onecompiler.io/43vzhtmas/43vzhswq7/lidyaa.jpg" alt="Foto Profil">
    <p>
      Saya adalah siswi yang bersekolah di SMKN 7 BATAM. Saya memilih konsentrasi keahlian Rekayasa Perangkat Lunak karena saya tertarik pada bidang programming.
    </p>
  </section>

  <section id="tentang">
    <h2>Tentang Saya</h2>
    <p>
      Saya memiliki tekat untuk mendalami dunia pemrograman web, desain modern, dan teknologi digital.
      Tujuan saya adalah terus berkembang dan membagikan pengetahuan kepada orang lain.
    </p>
  </section>
  
    <section id="pengalaman">
    <h2>Pengalaman Organisasi</h2>
    <p>
      Semasa SMP, saya aktif mengikuti ekstrakulikuler paskibra dan pramuka.
      Di paskibra, saya dan rekan saya berhasil meraih juara harapan 2, harapan 1, dan juara utama 1 di event COG dan KOMPASGAR.
    </p>
  </section>

  <section id="kontak">
    <h2>Kontak</h2>
    <p>
      Anda dapat menghubungi saya melalui email: <strong>lidyaastarr@gmail.com</strong>
      atau nomor kontak saya: <strong>+62 813 6357 2340</strong>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Lidya Star She Tobing.</p>
  </footer>
</body>
</html>
