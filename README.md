<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Prestige Dém - Votre déménagement en toute sérénité. Demandez un devis personnalisé et rapide.">
    <title>Prestige Dém - Demande de Devis</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>Prestige Dém</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#accueil">Accueil</a></li>
                    <li><a href="#services">Nos Services</a></li>
                    <li><a href="#devis">Demande de Devis</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Section d'accueil -->
    <section id="accueil">
        <div class="container">
            <h2>Bienvenue chez Prestige Dém</h2>
            <p>Votre déménagement en toute sérénité. Nous prenons soin de vos biens comme si c'était les nôtres.</p>
        </div>
    </section>

    <!-- Section Demande de Devis -->
    <section id="devis">
        <div class="container">
            <h2>Demandez votre devis personnalisé</h2>
            <form action="envoyer_devis.php" method="POST" id="formDevis">
                <label for="nom">Nom</label>
                <input type="text" id="nom" name="nom" required>

                <label for="prenom">Prénom</label>
                <input type="text" id="prenom" name="prenom" required>

                <label for="adresse_depart">Adresse de départ</label>
                <input type="text" id="adresse_depart" name="adresse_depart" required>

                <label for="adresse_arrivee">Adresse d'arrivée</label>
                <input type="text" id="adresse_arrivee" name="adresse_arrivee" required>

                <label for="telephone">Numéro de téléphone</label>
                <input type="tel" id="telephone" name="telephone" required>

                <label for="email">Adresse e-mail</label>
                <input type="email" id="email" name="email" required>

                <label for="date_demenagement">Date du déménagement</label>
                <input type="date" id="date_demenagement" name="date_demenagement" required>

                <label for="commentaire">Message supplémentaire</label>
                <textarea id="commentaire" name="commentaire"></textarea>

                <button type="submit">Envoyer ma demande</button>
            </form>
        </div>
    </section>

    <!-- Section Contact -->
    <section id="contact">
        <div class="container">
            <h2>Contactez-nous</h2>
            <p>Vous avez des questions ? N'hésitez pas à nous contacter :</p>
            <ul>
                <li>Email : <a href="mailto:contact@prestigedem.com">contact@prestigedem.com</a></li>
                <li>Téléphone : 01 23 45 67 89</li>
                <li>Adresse : 123 Rue de Paris, 75000 Paris</li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Prestige Dém | Tous droits réservés</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
