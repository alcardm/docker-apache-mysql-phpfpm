# Creating Apache, MySQL and PHP-FPM containers for a web application with Docker compose
[(Via)](http://www.inanzzz.com/index.php/post/su76/creating-apache-mysql-and-php-fpm-containers-for-a-web-application-with-docker-compose)
---

## Issues
Lines added at *docker/apache/httpd.conf* [(via)](https://stackoverflow.com/a/48717418) **Working**
```
    LoadModule mpm_event_module modules/mod_mpm_event.so
#   LoadModule mpm_prefork_module modules/mod_mpm_prefork.so
#   LoadModule mpm_worker_module modules/mod_mpm_worker.so
```

