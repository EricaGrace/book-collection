# 📚 book-collection

Une application Symfony 7 permettant de gérer une collection de livres.

## 🚀 Installation

```bash
git clone https://github.com/EricaGrace/book-collection.gitt
cd book-collection
composer install
cp .env .env.local
# Modifier DATABASE_URL dans .env.local
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
symfony server:start ou php -S 127.0.0.1:8000 -t public


📁 Structure du projet
src/Entity/Book.php — entité principale
src/Controller/BookController.php — logique de gestion des livres
templates/book — vues Twig
public/ — point d’entrée de l’application
config/ — configuration Symfony

🧪 Fonctionnalités
CRUD complet sur les livres
Architecture MVC Symfony
Interface Twig 

✨ Améliorations possibles
Pagination
Barre de recherche pour les livres par mots clés ou auteurs
Authentification
Rôles ( admin, user...)
visuel miniature des livres 
UI/UX