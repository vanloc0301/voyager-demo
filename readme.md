<a href="https://styleci.io/repos/76014128"><img src="https://styleci.io/repos/76014128/shield?style=flat" alt="Build Status"></a>

## VOYAGER DEMO PROJECT

This is a demo project using [Voyager](https://github.com/the-control-group/voyager) package for Laravel. Feel free to use, modify or whatever you like with this project.

What's included?
#### Products Module
- [x] Manage Product.
- [x] Manage Product Variation (sizes).
- [x] Manage Product Images. Drag n drop sortable image.
- [x] Product Categories.

#### Orders Module
- [ ] Manage Order.
- [ ] Manage Order Products.
- [ ] Order Events (Created, Ready to Ship, Shipped, Canceled).
- [ ] Product Stock Update.
- more..

#### Front-End web pages.
- [ ] E-commerce workflow

### Install:
You can [download latest release .zip file](https://github.com/handiwijoyo/voyager-demo/releases) or clone this project
```bash
git clone https://github.com/handiwijoyo/voyager-demo
```

Enter the voyager-demo directory
```bash
cd voyager-demo
```

Install composer dependencies:
```bash
composer install
```

Copy .env-example to .env:
```bash
cp .env.example .env
```

Generate application key:
```
php artisan key:generate
```

Update your database credentials in .env:
```bash
DB_HOST=localhost
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret
```

Run migration & seeder:
```bash
php artisan migrate --seed
```

Create a symbolic link from "public/storage" to "storage/app/public"
```bash
php artisan storage:link
```

(Optional) If you don't have webserver running you can use
```
php artisan serve
```

That's all. Now you may visit the website:
```
http://domain.dev/admin
```

Login:
```
email: admin@admin.com
password: password
```
