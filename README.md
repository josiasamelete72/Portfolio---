# Portfolio---
Portfolio de josias 
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio de Josias</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }
        h2 {
            color: #333;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 8px;
            font-size: 1em;
        }
        form button {
            padding: 10px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenue sur mon portfolio</h1>
    <p>Josias - Passionné par l'informatique et le numérique</p>
</header>

<nav>
    <a href="#competences">Compétences</a>
    <a href="#projets">Projets</a>
    <a href="#formations">Formations & Expériences</a>
    <a href="#contact">Contact</a>
</nav>

<section id="competences">
    <h2>Mes compétences</h2>
    <ul>
        <li>HTML / CSS (bases solides)</li>
        <li>Création de sites web simples</li>
        <li>Rédaction professionnelle</li>
        <li>Utilisation de Word / Excel / PowerPoint</li>
        <li>Maintenance informatique de base</li>
    </ul>
</section>

<section id="projets">
    <h2>Mes projets</h2>
    <ul>
        <li><strong>Portfolio personnel</strong> : Ce site web que vous consultez actuellement, réalisé entièrement en HTML et CSS.</li>
        <li><strong>Blog fictif</strong> : Création d'une maquette de blog personnel pour m'entraîner au webdesign.</li>
        <li><strong>Mini-application</strong> : Réalisation d'une petite calculatrice HTML / CSS / JavaScript (en local).</li>
    </ul>
</section>

<section id="formations">
    <h2>Formations & Expériences</h2>
    <h3>Formations</h3>
    <ul>
        <li>Baccalauréat informatique & Bureautique</li>
        <li>Formation en cybersécurité - en cours</li>
    </ul>

    <h3>Expériences</h3>
    <ul>
        <li>Chargé d'études - Ministère de la Planification (stage, section Union Européenne)</li>
        <li>Interventions ponctuelles en maintenance informatique</li>
    </ul>
</section>

<section id="contact">
    <h2>Me contacter</h2>
    <form action="#" method="post">
        <input type="text" name="name" placeholder="Votre nom" required>
        <input type="email" name="email" placeholder="Votre email" required>
        <textarea name="message" rows="5" placeholder="Votre message" required></textarea>
        <button type="submit">Envoyer</button>
    </form>
</section>

<footer>
    <p>© 2025 Josias - Tous droits réservés</p>
</footer>

</body>
</html>
