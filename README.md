
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
</style>
</head>
<body>

    <img src="Phi_Lemon_Dossier_2.jpg" alt="Phi Lemon Dossier 2">
    <img src="Phi_Lemon_Dossier.jpg" alt="Phi Lemon Dossier">

    <p><a href="https://bandcamp.com" target="_blank">Bandcamp Page</a></p>

    <form action="https://formspree.io/f/xpwdwoeo" method="POST">
        <p><label>Name:<br><input type="text" name="name" required></label></p>
        <p><label>E-Mail-Adress:<br><input type="email" name="email" required></label></p>
        <p><label>Message:<br><textarea name="message" rows="5" required></textarea></label></p>
        <p><button type="submit">Absenden</button></p>
    </form>

</body>
</html>
