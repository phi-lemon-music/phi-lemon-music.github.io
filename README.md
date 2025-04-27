<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Phi Lemon Music</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      text-align: center;
    }
    .container {
      max-width: 600px;
      margin: 0 auto;
    }
    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 0 auto;
    }
    .listen-section {
      margin-top: 50px; /* larger space above this section */
    }
    .listen-section p {
      margin: 0;
      font-size: 1.2em;
    }
    .listen-section img {
      margin-top: 5px; /* small spacing between text and icon */
      width: 50px;
      height: auto;
    }
    form {
      margin-top: 40px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    form label {
      width: 100%;
      text-align: left;
      margin-top: 10px;
      font-weight: bold;
    }
    form input,
    form textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      border: 1px solid #fff;
      background-color: #000;
      color: #fff;
      border-radius: 4px;
    }
    form button {
      margin-top: 15px;
      padding: 10px 20px;
      border: none;
      background-color: #fff;
      color: #000;
      font-size: 1em;
      cursor: pointer;
      border-radius: 4px;
    }
    form button:hover {
      background-color: #eee;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="Phi_Lemon_Dossier.jpg" alt="Phi Lemon Dossier Image 1">
    <img src="Phi_Lemon_Dossier_2.jpg" alt="Phi Lemon Dossier Image 2">

    <div class="listen-section">
      <p>Listen to Phi Lemon on</p>
      <img src="BandCamp_icon.png" alt="Bandcamp">
    </div>

    <form action="https://formspree.io/f/xpwdwoeo" method="POST">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" placeholder="Name" required>

      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" placeholder="Email Address" required>

      <label for="message">Message</label>
      <textarea id="message" name="message" rows="4" placeholder="Message" required></textarea>

      <button type="submit">Send</button>
    </form>
  </div>
</body>
</html>
