<html lang="de">
<head>
<meta charset="UTF-8">
<title>Meine GitHub Page</title>
<style>
body {
    background-color: #000;
    color: #fff;
    text-align: center;
    font-family: Arial, sans-serif; /* Normale Standardschrift */
}
img {
    max-width: 90%;
    height: auto;
    margin: 10px 0;
}
a {
    color: #1e90ff;
    text-decoration: none;
    font-size: 20px;
    display: inline-block;
    margin-top: 15px;
}
a:hover {
    text-decoration: underline;
}
input, textarea {
    margin: 5px 0;
    width: 80%;
    max-width: 400px;
    background-color: #333;
    color: #fff;
    border: 1px solid #555;
    padding: 10px;
}
button {
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #444;
    color: #fff;
    border: 1px solid #555;
    cursor: pointer;
}
button:hover {
    background-color: #555;
}
form {
    margin-top: 30px;
}
p {
    margin-top: 60px;
}
.tour-text {
    font-family: 'Courier New', Courier, monospace;
    font-size: 1.2em;
    margin: 30px 0;
}
.listen-section {
    margin-top: 20px;
}
.listen-section p {
    margin: 0;
    font-size: 1.5em;
    font-family: 'Courier New', Courier, monospace; /* Typewriter-Schrift */
}
.listen-section img {
    margin-top: 5px;
    width: 100px; /* Größeres Icon */
    height: auto;
}
.contact-section {
    margin-top: 60px;
}
.contact-section p {
    font-size: 1.5em;
    font-family: 'Courier New', Courier, monospace; /* Typewriter-Schrift */
}
</style>
</head>
<body>

    <img src="Phi_Lemon_Dossier.jpg" alt="Phi Lemon Dossier">

    <!-- Tour Text zwischen den Bildern -->
    <p class="tour-text">Japan Summer Tour 2025 — Dates coming soon…</p>

    <img src="Phi_Lemon_Dossier_2.jpg" alt="Phi Lemon Dossier 2">

    <div class="listen-section">
        <p>Listen to Phi Lemon on</p>
        <a href="https://bandcamp.com" target="_blank">
            <img src="BandCamp_icon.png" alt="Bandcamp">
        </a>
    </div>

    <div class="contact-section">
        <p>Contact:</p>
    </div>

    <form action="https://formspree.io/f/xpwdwoeo" method="POST">
        <p><label>Name:<br><input type="text" name="name" required></label></p>
        <p><label>E-Mail-Adress:<br><input type="email" name="email" required></label></p>
        <p><label>Message:<br><textarea name="message" rows="5" required></textarea></label></p>
        <p><button type="submit">Absenden</button></p>
    </form>

</body>
</html>
