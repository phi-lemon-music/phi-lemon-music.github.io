<html lang="de">
<head>
<meta charset="UTF-8">
<title>Meine GitHub Page</title>
<style>
body {
    background-color: #000;
    color: #fff;
    text-align: center;
    font-family: Arial, sans-serif;
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
    margin-top: 30px;
    margin-bottom: 30px;
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
</style>
</head>
<body>

    <img src="Phi_Lemon_Dossier.jpg" alt="Phi Lemon Dossier">
    <img src="Phi_Lemon_Dossier_2.jpg" alt="Phi Lemon Dossier 2">


    <!-- Text vor dem Icon -->
    <p>Listen to Phi Lemon on</p>
    <!-- Bandcamp-Icon -->
    <p>
        <a href="https://bandcamp.com" target="_blank">
            <img src="BandCamp_icon.png" alt="Bandcamp" style="width:80px; height:auto;">
        </a>
    </p>

    <form action="https://formspree.io/f/xpwdwoeo" method="POST">
        <p><label>Name:<br><input type="text" name="name" required></label></p>
        <p><label>E-Mail-Adress:<br><input type="email" name="email" required></label></p>
        <p><label>Message:<br><textarea name="message" rows="5" required></textarea></label></p>
        <p><button type="submit">Absenden</button></p>
    </form>

</body>
</html>
