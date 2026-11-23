FROM php:8.6.0RC7-apache

COPY index.php /var/www/html/
COPY init_container.sh /opt/

EXPOSE 80 

ENTRYPOINT [ "/opt/init_container.sh" ]