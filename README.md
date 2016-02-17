# install apache

install apache2 in terminal for ubuntu
>sudo apt-get install apache2

***
# config settings

>sudo vi /etc/apache2/apache2.conf
find the position of "<Directory /var/www/>" and change to new directory if necessary
>sudo vi /etc/apache2/sites-available/000-default.conf
find the position of "DocumentRoot /var/www/html" and change to new root directory if necessary

***
# restart

>sudo /etc/init.d/apache2 restart
