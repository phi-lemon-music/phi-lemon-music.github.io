<html lang="de">
<head>
<meta charset="UTF-8">
<title>Meine GitHub Page</title>
<style>
body {
    background-color: #000;
    color: #fff;
    text-align: center;
    font-family: 'Courier New', Courier, monospace;
    font-size: 44px;
}
img {
    max-width: 90%;
    height: auto;
    margin: 10px 0;
}
a {
    color: #1e90ff;
    text-decoration: none;
    font-size: 40px;
    display: inline-block;
    margin-top: 60px;
    margin-bottom: 60px;
}
a:hover {
    text-decoration: underline;
}
input, textarea {
    margin: 20px 0;
    width: 80%;
    max-width: 600px;
    background-color: #333;
    color: #fff;
    border: 1px solid #555;
    padding: 24px;
    font-size: 36px;
}
button {
    margin-top: 30px;
    padding: 24px 48px;
    background-color: #444;
    color: #fff;
    border: 1px solid #555;
    cursor: pointer;
    font-size: 36px;
}
button:hover {
    background-color: #555;
}
form {
    margin-top: 100px;
}
p {
    margin-top: 60px;
    margin-bottom: 60px;
}
.section-title {
    font-family: 'Courier New', Courier, monospace;
    font-size: 64px;
    margin-bottom: 20px;
}
.blink-text {
    font-size: 64px;
    color: #f4a9c0;
    animation: blink-animation 1.5s steps(5, start) infinite;
}
.blink-text2 {
    font-size: 64px;
    color: #fff;
    animation: none;
}
@keyframes blink-animation {
    50% {
        opacity: 0;
    }
}
</style>
</head>
<body>

    <img src="Phi_Lemon_Dossier.jpg" alt="Phi Lemon Dossier">

    <div style="height: 60px;"></div>

    <p class="blink-text">Japan Summer Tour 2025</p>

    <div style="height: 5px;"></div>

    <p class="blink-text2">Dates are coming soon</p>

    <div style="height: 20px;"></div>

    <img src="Phi_Lemon_Dossier_2.jpg" alt="Phi Lemon Dossier 2">

    <div style="height: 120px;"></div>

    <p class="section-title">Listen to Phi Lemon on</p>

    <p>
        <a href="https://bandcamp.com" target="_blank">
            <img src="BandCamp_icon.png" alt="Bandcamp" style="width:400px; height:auto;">
        </a>
    </p>

    <div style="height: 40px;"></div>

    <p class="section-title">Contact:</p>

    <form action="https://formspree.io/f/xpwdwoeo" method="POST">
        <p><label>Name:<br><input type="text" name="name" required></label></p>
        <p><label>E-Mail Address:<br><input type="email" name="email" required></label></p>
        <p><label>Message:<br><textarea name="message" rows="5" required></textarea></label></p>
        <p><button type="submit">Absenden</button></p>
    </form>

    <!-- Hier dein zusätzliches Bild ganz unten -->
    <div style="margin-top: 100px;">
        <img src="1745793875567_filtered 2.JPG" alt="Zusätzliches Bild">
    </div>

</body>
</html>
