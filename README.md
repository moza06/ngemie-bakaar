<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mie Bakar Blitar</title>
  <meta name="description" content="ngemie bakaar cilincing - Kedai mie kekinian dengan rasa menggoda dan konsep kontainer modern di Blitar.">
  <link rel="icon" href="favicon.png" type="image/png">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fffaf5;
      color: #333;
      overflow-x: hidden;
    }

    header {
      background: linear-gradient(135deg, #ff6b35, #ff9f68);
      color: white;
      padding: 2.5rem 1rem;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      animation: fadeIn 2s ease-in-out;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      animation: fadeIn 2.5s ease-in-out;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    .highlight {
      background-color: #ffe5d9;
      border-left: 4px solid #ff6b35;
      padding: 1.5rem;
      margin-bottom: 2rem;
      border-radius: 8px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .highlight:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
    }

    img {
      width: 100%;
      max-width: 700px;
      display: block;
      margin: 2rem auto;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    img:hover {
      transform: scale(1.05);
    }

    ul {
      list-style: none;
      margin: 0;
      padding: 0;
    }

    ul li {
      margin-bottom: 0.5rem;
      padding-left: 1.5rem;
      position: relative;
    }

    ul li::before {
      content: "✔";
      position: absolute;
      left: 0;
      color: #ff6b35;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      background: linear-gradient(135deg, #ff6b35, #ff9f68);
      color: white;
      margin-top: 2rem;
      box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.1);
    }

    footer p {
      margin: 0;
      font-size: 1rem;
    }

    a.cta {
      display: inline-block;
      padding: 0.8rem 1.5rem;
      background-color: #ff6b35;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      transition: transform 0.3s ease, background-color 0.3s ease;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      animation: bounce 2s infinite;
    }

    a.cta:hover {
      background-color: #ff9f68;
      transform: scale(1.05);
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
      }
      40% {
        transform: translateY(-10px);
      }
      60% {
        transform: translateY(-5px);
      }
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      header p {
        font-size: 1rem;
      }

      section {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>ngemie bakaar cilincing</h1>
    <p>Kuliner Kekinian, Rasa Menggoda</p>
  </header>
  <section>
    <div class="highlight">
      <h2>Konsep & Produk</h2>
      <p>Kedai mie bakar dalam kontainer modern dengan berbagai varian rasa dan level pedas, ditemani menu pelengkap dan minuman segar.</p>
    </div>
    <img src="file-XtEU5cxBTmAm4C91gh9evX" alt="desain1.jpg" loading="lazy">
    <img src="file-QxyWtoXBmGM2JE3QSiBVQE" alt="desain2.jpg" loading="lazy">
    <img src="file-3iJc1otfPgDktbVPLbb5ZS" alt="desain3.jpg" loading="lazy">
    <img src="file-Me1VtsgjkRoD5SyiQ6iaP2" alt="desain4.jpg" loading="lazy">
    <img src="file-8LX9ubBPCQ9ow637cG4pD3" alt="desain5.jpg" loading="lazy">

    <div class="highlight">
      <h2>Target Pasar & Lokasi</h2>
      <p>Anak muda, pelajar, pekerja, dan pecinta pedas di sekitar Blitar. Lokasi strategis dekat sekolah atau pusat keramaian.</p>
    </div>

    <div class="highlight">
      <h2>Estimasi Keuangan</h2>
      <ul>
        <li>Modal awal: Rp 20 – 30 juta</li>
        <li>Omzet harian: Rp 1 – 1,5 juta</li>
        <li>Laba bersih bulanan: Rp 10 – 15 juta</li>
      </ul>
    </div>

    <div class="highlight">
      <h2>Visi & Strategi</h2>
      <p>Rasa autentik, tempat nyaman, tema tempat yang istragramable, dan promosi digital untuk menjangkau lebih banyak pelanggan.</p>
      <a href="https://wa.me/6285854438411" target="_blank" class="cta">Coba Sekarang!</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Mie Bakar Blitar. All rights reserved.</p>
  </footer>
</body>
</html>
