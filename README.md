<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dépanange électrotechnique</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Dépanange électrotechnique<br>Prestataire de services</h1>
            <p>Industrie - Bâtiment - Agricole</p>
            <p>Électricité - Mécanique - Hydraulique</p>
            <p class="phone-number">06 63 93 82 73</p>
        </div>
    </header>

    <section class="form-section">
        <h2>Ets Yoann LE BESCO</h2>
        <p>Email : yoannlebesco@gmail.com</p>
        <p>SIRET : 81123800500011 3312Z</p>
        <p>Tél : 06 63 93 82 73</p>

        <form action="#" method="post">
            <label for="company">Votre nom entreprise (facultatif)</label>
            <input type="text" id="company" name="company">

            <label for="name">Votre nom (obligatoire)</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Votre email (obligatoire)</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Votre téléphone (facultatif)</label>
            <input type="tel" id="phone" name="phone">

            <label for="service">Types Interventions</label>
            <select id="service" name="service">
                <option value="electromeca">Dépannage électromécanique</option>
                <!-- Ajouter d'autres options si nécessaire -->
            </select>

            <label for="subject">Sujet</label>
            <input type="text" id="subject" name="subject">

            <label for="message">Votre message</label>
            <textarea id="message" name="message"></textarea>

            <button type="submit">Envoyer</button>
        </form>
    </section>

    <section class="map-section">
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2633.936934394207!2d-1.7208573844421545!3d48.35733137923819!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x480ef01b888f8b73%3A0x1bc88e0b235b5d50!2sOlivet%2C%2021310%20Bourseul!5e0!3m2!1sfr!2sfr!4v1602289927434!5m2!1sfr!2sfr"
            width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy">
        </iframe>
    </section>
</body>
</html>

CSS (Style de la page)

/* style.css */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}

header {
    background-color: #e1e1e1;
    text-align: center;
    padding: 20px;
}

.header-content h1 {
    font-size: 24px;
    color: #333;
    margin: 0;
}

.header-content p {
    font-size: 16px;
    color: #666;
}

.phone-number {
    font-weight: bold;
    font-size: 20px;
    color: #333;
}

.form-section {
    background-color: #ffffff;
    width: 80%;
    margin: 20px auto;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.form-section h2 {
    font-size: 20px;
    margin-bottom: 10px;
}

form label {
    display: block;
    margin-top: 10px;
    font-weight: bold;
}

form input, form select, form textarea {
    width: 100%;
    padding: 8px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    margin-top: 10px;
}

form button:hover {
    background-color: #555;
}

.map-section {
    text-align: center;
    margin-top: 20px;
}

