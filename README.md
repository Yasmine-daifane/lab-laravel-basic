# Lab Laravel Basique

## Ce dépôt présente un projet Laravel de base pour la gestion de projets, mettant l'accent sur la gestion des tâches.
### Le travail à Fiare :

- Opérations CRUD pour les tâches
- Pagination
- Recherche (AJAX)
- Base de données : comportant deux tables, tâches et projets (seeders)
- Filtrage par projets



<!-- ## Les Commands -->
## Installation Laravel 

```bash
composer create-project laravel/laravel .
```

## Databases
### 1. Env

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=live_coding_larave_lcrud_basic
DB_USERNAME=root
DB_PASSWORD=solicoders
```



## Model

```bash
php artisan make:model Project -m
php artisan make:model Task -m
```

```bash
php artisan make:seeder TaskSeeder
php artisan make:seeder ProjectSeeder


```

```bash
php artisan db:seed

```

## Controller
```bash
php artisan make:controller TaskController -r


```

```bash
php artisan make:view Tasks.index
php artisan make:view Tasks.create
php artisan make:view Tasks.edit
```
## Views
```bash
php artisan make:view Layouts.Layout
php artisan make:view Layouts.Footer
php artisan make:view Layouts.Navbar
php artisan make:view Layouts.Sidebar
php artisan make:view Layouts.Error404
```

## Livrable 
[Presentation lab-crude-laravel-basic](https://docs.google.com/presentation/d/16O9Q0SP7jeOPpMSTtWhGdpNF_AXEBORxemt-UoJAIe0/edit?usp=sharing)
