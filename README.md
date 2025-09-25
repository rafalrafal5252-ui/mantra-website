<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MANTRA | Angry Beatdown Hardcore</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>MANTRA</h1>
    <p class="tagline">Angry Beatdown Hardcore</p>
    <a href="#music" class="btn">Listen Now</a>
  </header>

  <section id="about">
    <h2>About</h2>
    <p>MANTRA is an Angry Beatdown Hardcore band screaming about freedom, reality, and the raw truths of life. We don't sugarcoat — we confront. Welcome to the noise.</p>
  </section>

  <section id="music">
    <h2>Music</h2>
    <p>Check out our latest tracks:</p>
    <!-- Embed your music player below -->
    <iframe style="border: 0; width: 100%; height: 120px;" src="https://open.spotify.com/embed/artist/your-band-id" allowtransparency="true" allow="encrypted-media"></iframe>
  </section>

  <section id="media">
    <h2>Photos / Videos</h2>
    <img src="your-photo.jpg" alt="MANTRA Live" style="max-width:100%; height:auto;" />
    <!-- Add more photos or YouTube embeds -->
  </section>

  <section id="contact">
    <h2>Follow & Contact</h2>
    <ul class="socials">
      <li><a href="[https://instagram.com/yourband](https://www.instagram.com/somethingthaticallmantra?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==)" target="_blank">Instagram</a></li>
      <li><a href="mailto:rafalrafal5252@gmail.com">Email Us</a></li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 MANTRA. No compromise. No silence.</p>
  </footer>
</body>
</html>
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #0d0d0d;
  color: #f5f5f5;
  line-height: 1.6;
}

header {
  background: url('your-background.jpg') no-repeat center center/cover;
  text-align: center;
  padding: 100px 20px;
  color: #f5f5f5;
}

header h1 {
  font-size: 4rem;
  letter-spacing: 4px;
  margin-bottom: 10px;
}

.tagline {
  font-size: 1.5rem;
  font-style: italic;
  color: #e63946;
}

.btn {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  color: #f5f5f5;
  background: #e63946;
  text-decoration: none;
  border-radius: 5px;
}

section {
  padding: 60px 20px;
  max-width: 800px;
  margin: auto;
}

h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #e63946;
}

.socials {
  list-style: none;
  padding: 0;
}

.socials li {
  margin-bottom: 10px;
}

.socials a {
  color: #f5f5f5;
  text-decoration: none;
  font-weight: bold;
}

footer {
  background: #111;
  text-align: center;
  padding: 20px;
  font-size: 0.9rem;
  color: #888;
}

