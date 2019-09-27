# SymphArt

> A basic Symfony 4 CRUD application used in the tutorial series "Up & Running With Symfony 4"

## Quick Start

``` bash
# Install dependencies
composer install

# Edit the env file and add DB params

# Create Article schema
php bin/console doctrine:migrations:diff
# Run migrations
php bin/console doctrine:migrations:migrate

# Build for production
npm run build

# Run symfony server 
symfony server:start

```

## App Info

### Author

Brad Traversy
[Traversy Media](http://www.traversymedia.com)

### Version

1.0.0

### License

This project is licensed under the MIT License
