# simple-nginx-php-docker

Files for creating a Docker container using docker-compose with lastest nginx/php with fpm.

This was my first experience using Docker to create a PHP environment so note there could be a more efficient way of doing this. I wanted a starting point for future projects using Docker.

The hosts file will need to be updated with information replicating the `site.conf` `server_name` which in this case is `php-docker.local`

Apart from that running `docker-compose up` will download everything needed at their latest hash values.
