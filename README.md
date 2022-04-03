# Application Name

Application description

![Alt text](https://via.placeholder.com/1024x768?text=Image+Here)

## Prerequisites

* Php 8.0.2 or up
* {Items here}
## Run Locally

Clone the repository and go to {application directory} directory
```shell
git clone https://github.com/{username}/{repository name}.git

cd {application directory}
```

Generate .env file
```shell
cp .env.example .env
```

Then, configure the .env file according to your use case.

Install the dependencies and then compile the assets
```shell
composer install

npm install
npm run dev
```

Populate the tables and the data to the database
```shell
php artisan migrate --seed
```

Generate app key
```shell
php artisan key:generate
```

Run the application
```shell
php artisan serve
```
Finally, visit http://localhost:8000 to view the site.
