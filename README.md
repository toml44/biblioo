<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblio-Drive Moulinsart</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
    <p>La Bibliothèque de Moulinsort est fermée au public jusqu'à nouvel ordre.Mais il vous est possible de réserver et retirer vos livres via notre service Biblio Drive!</p>
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container">
            <a class="navbar-brand" href="index.html">Biblio-Drive</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="index.html">Accueil</a>
                    </li>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Rechercher un auteur" required>
                    <button class="btn btn-outline-light" type="submit">Rechercher</button>
                </form>
            </div>
        </div>
    </nav>

    <div class="container mt-4">
        <div class="row">
            <div class="col-md-8">
                <div id="carouselLatestBooks" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselLatestBooks" data-bs-slide-to="0" class="active"></button>
                        <button type="button" data-bs-target="#carouselLatestBooks" data-bs-slide-to="1"></button>
                        <button type="button" data-bs-target="#carouselLatestBooks" data-bs-slide-to="2"></button>
                    </div>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://static.fnac-static.com/multimedia/FR/Images_Produits/FR/fnac.com/Visual_Principal_340/0/2/4/9782354251420/tsp20130326163652/Le-livre-de-Homer-encyclopedie-Simpson-du-savoir.jpg" alt="First slide" class="d-block w-100" alt="Les Misérables">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Homer</h5>
                                <p></p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="https://m.media-amazon.com/images/I/81Q5YfdUgsL._AC_UF1000,1000_QL80_.jpg" alt="Second slide" class="d-block w-100" alt="L'Étranger">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Titeuf</h5>
                                <p></p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="" class="d-block w-100" alt="Germinal">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Germinal</h5>
                                <p>Par Émile Zola</p>
                            </div>
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselLatestBooks" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                        <span class="visually-hidden">Précédent</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselLatestBooks" data-bs-slide="next">
                        <span class="carousel-control-next-icon"></span>
                        <span class="visually-hidden">Suivant</span>
                    </button>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-header">
                        <h5 class="card-title mb-0">Connexion</h5>
                    </div>
                    <div class="card-body">
                        <form>
                            <div class="mb-3">
                                <label for="email" class="form-label">Email</label>
                                <input type="email" class="form-control" id="email" required>
                            </div>
                            <div class="mb-3">
                                <label for="password" class="form-label">Mot de passe</label>
                                <input type="password" class="form-control" id="password" required>
                            </div>
                            <button type="submit" class="btn btn-primary">Se connecter</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-light mt-5 py-3">
        <div class="container">
            <div class="text-center">
                <p>&copy; 2024 Biblio-Drive </p>
            </div>
        </div>
    </footer>
</body>
</html>
