<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Profil X-Rezz</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background: #f8f9fa;
      color: #333;
      line-height: 1.6;
      padding: 40px 20px;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 40px;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 12px 40px rgba(0, 0, 0, 0.1);
      animation: fadeIn 1s ease-in-out;
      overflow: hidden;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    .profile {
      text-align: center;
      margin-bottom: 30px;
    }

    .profile img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 5px solid #2980b9;
      object-fit: cover;
      transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
    }

    .profile img:hover {
      transform: scale(1.1);
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.2);
    }

    h1 {
      font-size: 2.8rem;
      color: #2980b9;
      margin-top: 20px;
      letter-spacing: 1px;
      text-transform: uppercase;
      font-weight: bold;
      animation: fadeInText 1.5s ease-out;
    }

    @keyframes fadeInText {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h2 {
      font-size: 1.9rem;
      color: #16a085;
      margin-top: 10px;
      font-weight: 500;
    }

    .badge {
      display: inline-block;
      background: #e74c3c;
      color: #fff;
      padding: 8px 20px;
      border-radius: 25px;
      font-size: 14px;
      margin-top: 10px;
      animation: bounce 1.5s infinite;
    }

    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-8px);
      }
    }

    hr {
      border: 1px solid #ddd;
      margin: 30px 0;
      opacity: 0.6;
    }

    .stats img, .languages img, .streak img {
      width: 100%;
      max-width: 100%;
      border-radius: 12px;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .stats img:hover, .languages img:hover, .streak img:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
    }

    .stats, .languages, .contributions, .streak {
      margin: 30px 0;
    }

    .languages table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    .languages table, th, td {
      border: 1px solid #ddd;
      padding: 15px;
      text-align: left;
      font-size: 1.1rem;
      transition: background-color 0.3s ease;
    }

    th {
      background-color: #2980b9;
      color: white;
      font-weight: bold;
    }

    tr:nth-child(even) {
      background-color: #f9f9f9;
    }

    tr:hover {
      background-color: #ecf0f1;
    }

    .footer {
      text-align: center;
      font-size: 1.2rem;
      margin-top: 40px;
      color: #7f8c8d;
      font-weight: 500;
    }

    .footer a {
      color: #2980b9;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    .footer a:hover {
      color: #16a085;
    }

    .contributions ul {
      list-style-type: none;
      padding-left: 0;
    }

    .contributions li {
      margin: 12px 0;
      font-size: 1.2rem;
      color: #34495e;
    }

    .contributions li strong {
      color: #2980b9;
    }

    /* Media Queries for responsiveness */
    @media (max-width: 768px) {
      .container {
        padding: 20px;
      }
      h1 {
        font-size: 2.2rem;
      }
      h2 {
        font-size: 1.6rem;
      }
      .profile img {
        width: 130px;
        height: 130px;
      }
    }

    @media (max-width: 480px) {
      .container {
        padding: 15px;
      }
      h1 {
        font-size: 1.8rem;
      }
      h2 {
        font-size: 1.4rem;
      }
      .profile img {
        width: 100px;
        height: 100px;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Profile Section -->
    <div class="profile">
      <img src="https://via.placeholder.com/150" alt="Profile Picture">
      <h1>👋 Halo, Selamat Datang di Profil Saya!</h1>
      <span class="badge">GitHub API-call error</span>
    </div>

    <hr>

    <!-- GitHub Stats Section -->
    <div class="stats">
      <h2>📊 Statistik GitHub X-Rezz</h2>
      <img src="https://github-readme-stats.vercel.app/api?username=RerezzOfficial&show_icons=true&theme=radical&count_private=true&hide=prs,issues&include_all_commits=true" alt="GitHub Stats">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RerezzOfficial&layout=compact&langs_count=8&theme=radical" alt="GitHub Grade">
    </div>

    <hr>

    <!-- GitHub Streak Section -->
    <div class="streak">
      <h2>🔥 Streak GitHub</h2>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=RerezzOfficial&theme=dark&hide_border=true" alt="GitHub Streak">
    </div>

    <hr>

    <!-- Contributions Section -->
    <div class="contributions">
      <h2>🏆 Kontribusi Total</h2>
      <ul>
        <li><strong>Total Kontribusi:</strong> 196</li>
        <li><strong>Streak Saat Ini (Nov 11 - Nov 15):</strong> 5 hari</li>
        <li><strong>Streak Terpanjang (Sep 13 - Sep 17):</strong> 5 hari</li>
      </ul>
    </div>

    <hr>

    <!-- Most Used Languages Section -->
    <div class="languages">
      <h2>🌐 Bahasa yang Paling Sering Digunakan</h2>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RerezzOfficial&langs_count=6&theme=radical&layout=compact" alt="Most Used Languages">

      <h3>Breakdown Penggunaan Bahasa</h3>
      <table>
        <thead>
          <tr>
            <th>Bahasa</th>
            <th>Penggunaan</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>HTML</td>
            <td>52.86%</td>
          </tr>
          <tr>
            <td>Shell</td>
            <td>32.84%</td>
          </tr>
          <tr>
            <td>Hack</td>
            <td>8.92%</td>
          </tr>
          <tr>
            <td>PHP</td>
            <td>2.97%</td>
          </tr>
          <tr>
            <td>CSS</td>
            <td>2.42%</td>
          </tr>
        </tbody>
      </table>
    </div>

    <hr>

    <!-- Footer Section -->
    <div class="footer">
      <p>Terima kasih telah mengunjungi profil saya! 🌟 Jangan lupa untuk memberi ⭐ pada proyek yang Anda suka! 😄</p>
      <p><a href="https://github.com/RerezzOfficial" target="_blank">Kunjungi Profil GitHub Saya</a></p>
    </div>
  </div>

</body>
</html>
