### Based on [https://gitlab.com/ric_harvey/nginx-php-fpm](https://gitlab.com/ric_harvey/nginx-php-fpm)

Docker container image with NGINX, PHP 7.2 and PHP-FPM, ideal for working with Laravel or Lumen projects, because the NGINX root directory points to /var/www/public, so you just have to mount your Laravel/Lumen project directory to /var/www:

```bash
docker run -v my_project_path:/var/www -p 8080:80 -d erodriguezds/nginx-php-fpm
```
