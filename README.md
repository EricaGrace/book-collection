# 📚 book-collection

Une application Symfony 7 permettant de gérer une collection de livres.

## 🚀 Installation

```bash
git clone https://github.com/votre-utilisateur/book-collection.git
cd book-collection
composer install
cp .env .env.local
# Modifier DATABASE_URL dans .env.local
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
symfony server:start
