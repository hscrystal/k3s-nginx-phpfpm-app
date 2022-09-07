# K3s Nginx PHP-FPM App on Raspberry Pi Cluser

In this tutorial, we will deploy a PHP application on a K3s cluster with Nginx and PHP-FPM running in separate containers.

We want the web-server nginx and phpfpm to be co-located in separate pods.
![alt text](https://i.ibb.co/R4P9YB0/kubernetes-nginx-phpfpm1-drawio.png)

### PHP-FPM
PHP-FPM is an implementation of Fast-CGI for PHP with improved capabilities around process management, logging, and high traffic situations.

### Nginx
Nginx is a web server and reverse proxy that’s widely used for high traffic applications. When run in combination with PHP-FPM, Nginx is configured to send requests for .php routes to PHP-FPM to serve the page.

