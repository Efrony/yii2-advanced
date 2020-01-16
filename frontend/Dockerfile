FROM yiisoftware/yii2-php:7.2-apache

EXPOSE 80;
EXPOSE 8081;

# Change document root for Apache
RUN sed -i -e 's|/app/web|/app/frontend/web|g' /etc/apache2/sites-available/000-default.conf
