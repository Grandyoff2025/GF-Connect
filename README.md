GF-CONNECT 

<!DOCTYPE html>
<html lang="français/Wolof/Anglais">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Digitalisation des États Civils – Mairie de Grand Yoff</title>
  <!-- Bootstrap CSS via CDN -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body { padding-top: 70px; }
    footer { background-color: #343a40; color: #fff; }
  </style>
</head>
<body>
  <!-- Barre de navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
    <a class="navbar-brand" href="index.html">Mairie Grand Yoff</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" 
            aria-controls="navbarNav" aria-expanded="false" aria-label="Basculer la navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="#accueil">Accueil</a></li>
        <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav> 

  <!-- Contenu principal -->
  <main class="container">
    <!-- Section Accueil -->
    <section id="accueil" class="mb-5">
      <h1>Bienvenue sur le portail des États Civils</h1>
      <p>
        Ce site a pour objectif de moderniser et sécuriser vos démarches administratives pour les actes d’état civil (naissance, mariage, décès). 
        Conçu pour être accessible, rapide et facile à utiliser, il vous guide pas à pas dans la digitalisation de vos démarches.
      </p>
    </section> 

    <!-- Section Services -->
    <section id="services" class="mb-5">
      <h2>Nos Services</h2>
      <div class="card-deck">
        <!-- Service Naissance -->
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Déclaration de Naissance</h5>
            <p class="card-text">Remplissez le formulaire pour déclarer une naissance de manière rapide et sécurisée.</p>
            <a href="naissance.html" class="btn btn-primary">Accéder au formulaire</a>
          </div>
        </div>
        <!-- Service Mariage -->
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Déclaration de Mariage</h5>
            <p class="card-text">Procédez à la demande de mariage via un processus simplifié et protégé.</p>
            <a href="mariage.html" class="btn btn-primary">Accéder au formulaire</a>
          </div>
        </div>
        <!-- Service Décès -->
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Déclaration de Décès</h5>
            <p class="card-text">Enregistrez le décès d’un proche en toute sécurité, 24/7, via notre portail.</p>
            <a href="deces.html" class="btn btn-primary">Accéder au formulaire</a>
          </div>
        </div>
      </div>
    </section> 

    <!-- Section Contact -->
    <section id="contact" class="mb-5">
      <h2>Contact</h2>
      <p>Pour toute question ou demande d'assistance, merci de nous contacter :</p>
      <form id="contactForm">
        <div class="form-group">
          <label for="contactNom">Nom</label>
          <input type="text" class="form-control" id="contactNom" placeholder="Votre nom" required>
        </div>
        <div class="form-group">
          <label for="contactEmail">Adresse Email</label>
          <input type="email" class="form-control" id=" GF-CONNECT@gmail.com " placeholder=" boysarr@gmail.com" required>
        </div>
        <div class="form-group">
          <label for="contactMessage">Message</label>
          <textarea class="form-control" id="contactMessage" rows="3" placeholder="Votre message" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Envoyer</button>
      </form>
    </section>
  </main> 

  <!-- Pied de page -->
  <footer class="py-3 text-center">
  </footer> 

  <!-- Inclusion des scripts Bootstrap et JS personnalisé -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <script>
    // Exemple de gestion de soumission du formulaire contact
    document.getElementById("contactForm").addEventListener("submit", function(event) {
      event.preventDefault();
      alert("Votre message a bien été envoyé. Nous vous répondrons dans les plus brefs délais.");
      this.reset();
    });
  </script>
</body>
</html>









  <title>Déclaration de Naissance – Mairie de Grand Yoff</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body { padding-top: 70px; }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
    <a class="navbar-brand" href="index.html">Mairie Grand Yoff</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Basculer la navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="index.html#accueil">Accueil</a></li>
        <li class="nav-item"><a class="nav-link" href="index.html#services">Services</a></li>
      </ul>
    </div>
  </nav> 

  <!-- Contenu principal -->
  <main class="container">
    <h1 class="mt-4">Déclaration de Naissance</h1>
    <p>Veuillez remplir le formulaire ci-dessous pour déclarer une naissance.</p>
    <form id="naissanceForm">
      <div class="form-group">
        <label for="nomEnfant">Nom de l'enfant</label>
        <input type="text" class="form-control" id="nomEnfant" placeholder="Nom de l'enfant" required>
      </div>
      <div class="form-group">
        <label for="prenomEnfant">Prénom de l'enfant</label>
        <input type="text" class="form-control" id="prenomEnfant" placeholder="Prénom de l'enfant" required>
      </div>
      <div class="form-group">
        <label for="dateNaissance">Date de naissance</label>
        <input type="date" class="form-control" id="dateNaissance" required>
      </div>
      <div class="form-group">
        <label for="lieuNaissance">Lieu de naissance</label>
        <input type="text" class="form-control" id="lieuNaissance" placeholder="Ville, commune" required>
      </div>
      <div class="form-group">
        <label for="nomParent">Nom du/de la parent</label>
        <input type="text" class="form-control" id="nomParent" placeholder="Nom complet du parent" required>
      </div>
      <div class="form-group">
        <label for="documentNaissance">Joindre un document (scan, PDF)</label>
        <input type="file" class="form-control-file" id="documentNaissance">
      </div>
      <button type="submit" class="btn btn-primary">Envoyer la déclaration</button>
    </form>
  </main> 

  <!-- Pied de page -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Mairie de Grand Yoff. Tous droits réservés.</p>
  </footer> 

  <!-- Scripts Bootstrap -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <script>
    // Gestion de la soumission du formulaire de naissance
    document.getElementById("naissanceForm").addEventListener("submit", function(event) {
      event.preventDefault();
      alert("Votre déclaration de naissance a été envoyée avec succès.");
      this.reset();
    });
  </script>
</body>
</html>







  <title>Déclaration de Mariage – Mairie de Grand Yoff</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body { padding-top: 70px; }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
    <a class="navbar-brand" href="index.html">Mairie Grand Yoff</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Basculer la navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="index.html#accueil">Accueil</a></li>
        <li class="nav-item"><a class="nav-link" href="index.html#services">Services</a></li>
      </ul>
    </div>
  </nav> 

  <!-- Contenu principal -->
  <main class="container">
    <h1 class="mt-4">Déclaration de Mariage</h1>
    <p>Veuillez remplir le formulaire ci-dessous pour déclarer un mariage.</p>
    <form id="mariageForm">
      <div class="form-group">
        <label for="nomConjoint1">Nom et Prénom du premier conjoint</label>
        <input type="text" class="form-control" id="nomConjoint1" placeholder="Nom et prénom" required>
      </div>
      <div class="form-group">
        <label for="nomConjoint2">Nom et Prénom du second conjoint</label>
        <input type="text" class="form-control" id="nomConjoint2" placeholder="Nom et prénom" required>
      </div>
      <div class="form-group">
        <label for="dateMariage">Date du mariage</label>
        <input type="date" class="form-control" id="dateMariage" required>
      </div>
      <div class="form-group">
        <label for="lieuMariage">Lieu du mariage</label>
        <input type="text" class="form-control" id="lieuMariage" placeholder="Ville, commune" required>
      </div>
      <div class="form-group">
        <label for="documentMariage">Joindre un document (scan, PDF)</label>
        <input type="file" class="form-control-file" id="documentMariage">
      </div>
      <button type="submit" class="btn btn-primary">Envoyer la déclaration</button>
    </form>
  </main> 

  <!-- Pied de page -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Mairie de Grand Yoff. Tous droits réservés.</p>
  </footer> 

  <!-- Scripts Bootstrap -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <script>
    // Gestion de la soumission du formulaire de mariage
    document.getElementById("mariageForm").addEventListener("submit", function(event) {
      event.preventDefault();
      alert("Votre déclaration de mariage a été envoyée avec succès.");
      this.reset();
    });
  </script>
</body>
</html>





<title>Déclaration de Décès – Mairie de Grand Yoff</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    body { padding-top: 70px; }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
    <a class="navbar-brand" href="index.html">Mairie Grand Yoff</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Basculer la navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="index.html#accueil">Accueil</a></li>
        <li class="nav-item"><a class="nav-link" href="index.html#services">Services</a></li>
      </ul>
    </div>
  </nav> 

  <!-- Contenu principal -->
  <main class="container">
    <h1 class="mt-4">Déclaration de Décès</h1>
    <p>Veuillez remplir le formulaire ci-dessous pour déclarer un décès.</p>
    <form id="decesForm">
      <div class="form-group">
        <label for="nomDefunt">Nom et Prénom du défunt</label>
        <input type="text" class="form-control" id="nomDefunt" placeholder="Nom et prénom" required>
      </div>
      <div class="form-group">
        <label for="dateDeces">Date du décès</label>
        <input type="date" class="form-control" id="dateDeces" required>
      </div>
      <div class="form-group">
        <label for="lieuDeces">Lieu du décès</label>
        <input type="text" class="form-control" id="lieuDeces" placeholder="Ville, commune" required>
      </div>
      <div class="form-group">
        <label for="documentDeces">Joindre un document (scan, PDF)</label>
        <input type="file" class="form-control-file" id="documentDeces">
      </div>
      <button type="submit" class="btn btn-primary">Envoyer la déclaration</button>
    </form>
  </main> 

  <!-- Pied de page -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Mairie de Grand Yoff. Tous droits réservés.</p>
  </footer> 

  <!-- Scripts Bootstrap -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <script>
    // Gestion de la soumission du formulaire de décès
    document.getElementById("decesForm").addEventListener("submit", function(event) {
      event.preventDefault();
      alert("Votre déclaration de décès a été envoyée avec succès.");
      this.reset();
    });
  </script>
</body>
</html>