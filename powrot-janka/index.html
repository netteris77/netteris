from zipfile import ZipFile
import shutil

# Ścieżki plików
html_path = "/mnt/data/index.html"
img_path = "/mnt/data/janek czekamy na ciebie!!.jpg"
zip_path = "/mnt/data/powrot-janka-strona.zip"

# Zapisujemy HTML do pliku
html_content = """<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>POWRÓT JANKA</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: black;
      color: white;
      font-family: 'Arial', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      overflow: hidden;
    }

    h1 {
      font-size: 4rem;
      margin-bottom: 20px;
      color: #ff0000;
    }

    #countdown {
      font-size: 2rem;
      margin-bottom: 10px;
    }

    #subtext {
      font-size: 1.5rem;
      margin-bottom: 30px;
      color: #ffd700;
    }

    img {
      width: 300px;
      border-radius: 20px;
      box-shadow: 0 0 30px red;
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>
  <h1>POWRÓT JANKA</h1>
  <div id="countdown"></div>
  <div id="subtext">CZEKAMY NA CIEBIE!</div>
  <audio autoplay loop>
    <source src="https://cdn.pixabay.com/download/audio/2023/03/01/audio_1fbc06e6ab.mp3?filename=epic-cinematic-heroic-trailer-139763.mp3" type="audio/mpeg">
    Twoja przeglądarka nie obsługuje audio :(
  </audio>
  <img src="janek czekamy na ciebie!!.jpg" alt="Janek na motocyklu">

  <script>
    const countdown = document.getElementById('countdown');
    const targetDate = new Date('2025-04-13T00:00:00');

    function updateCountdown() {
      const now = new Date();
      const diff = targetDate - now;

      if (diff <= 0) {
        countdown.textContent = "JUŻ JEST!";
        return;
      }

      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff / (1000 * 60 * 60)) % 24);
      const minutes = Math.floor((diff / (1000 * 60)) % 60);
      const seconds = Math.floor((diff / 1000) % 60);

      countdown.textContent = `${days}d ${hours}h ${minutes}m ${seconds}s`;
    }

    updateCountdown();
    setInterval(updateCountdown, 1000);
  </script>
</body>
</html>
"""

# Zapisz HTML do pliku
with open(html_path, "w", encoding="utf-8") as f:
    f.write(html_content)

# Spakuj HTML i zdjęcie do ZIP
with ZipFile(zip_path, "w") as zipf:
    zipf.write(html_path, arcname="index.html")
    zipf.write(img_path, arcname="janek czekamy na ciebie!!.jpg")

zip_path
