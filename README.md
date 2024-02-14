# LM Create

LM Create is a complete module create for Laravel.

## # Using Artisan
### To create a project:
```bash
php artisan create:project ProjectName
```

### To create a module:
```bash
php artisan create:module MyProject MyModule
```

### To create a scaffold:
```bash
php artisan create:skeleton MyProject MyModule
```

---

### If you need compound names, use " ' " with space
eg:
```bash
php artisan create:project 'My Project'
```
This is valid for Projects, Modules and Skeleton

----
## # Using PHP

### To create a project:
```bash
php index.php -f project:Project
```

### To create a module:
```bash
php index.php -f module:MyProject:MyModule
```

### To create a scaffold:
```bash
php index.php -f skeleton:MyProject:MyModule
```

---
### If you need compound names, use " ' " with space
eg:
```bash
php index.php -f project:'My Project'
```
This is valid for Projects, Modules and Skeleton