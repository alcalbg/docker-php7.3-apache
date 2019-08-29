# docker-php7.3-apache
Docker image with old php 7.3 running on apache2 with usual php extensions:

- php7.3
- php7.3-bcmath
- php7.3-curl
- php7.3-gd
- php7.3-mbstring
- php7.3-mysql
- php7.3-sqlite3
- php7.3-soap
- php7.3-xml
- php7.3-zip
- php7.3-xdebug

Based on Debian stretch

# sample usage
`docker run -d -v /var/www/html:/var/www/html -p 8000:80 alcalbg/php7.3-apache`

visit http://localhost:8000/
