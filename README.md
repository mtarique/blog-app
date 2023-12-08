# docker-laravel

Run docker and build:

docker compose up -d --build

Run command line in container:

docker compose run --rm php /bin/sh

Create laravel project via composer:

docker compose run --rm composer create-project laravel/laravel .

If access Forbidden:

docker compose run --rm php /bin/sh

and then - 

chown -R laravel:laravel /var/www/html

Source: https://vshloda.medium.com/setting-up-a-laravel-10-development-environment-with-docker-3977a292c8dd
Repository: https://github.com/vshloda/docker-laravel/blob/main/.gitignore
