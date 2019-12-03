# php-server-docker
Apache and PHP on Docker

This docker file is created using example on https://writing.pupius.co.uk/apache-and-php-on-docker-44faef716150

I made couple minor changes on the docker file. Such as defining repository for PHP7.

Example - Build Image :

docker build -t mysite .

Example - Start Container :

docker run -p 8080:80 -d mysite
