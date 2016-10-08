# install apache

install apache2 in terminal for ubuntu
>$ sudo apt-get install apache2

***
# config settings

find the position of "\<Directory /var/www/\>" and change to new directory if necessary

>$ sudo vi /etc/apache2/apache2.conf

find the position of "DocumentRoot /var/www/html" and change to new root directory if necessary

>$ sudo vi /etc/apache2/sites-available/000-default.conf

restart apache if config changed

>$ sudo /etc/init.d/apache2 restart

change the www folder to user workspaces

>$ sudo rm -r /var/www

>$ sudo ln -s ~/catkin_ws/www /var/www
