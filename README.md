# multiple-php-in-linux

        apt-get update && apt-get upgrade

        apt-get install -y software-properties-common

        add-apt-repository ppa:ondrej/php
        
        apt-get update

        apt-get install -y php5.6

______________________________
a2dismod php7.0 ; a2enmod php5.6 ; service apache2 restart

a2dismod php5.6 ; a2enmod php7.0 ; service apache2 restart
______________________________

        update-alternatives --config php

        php -v


         sudo service apache2 restart

         cd /etc/apache2
         apache2ctl configtest

         apachectl restart

         sudo a2enmod php7.2
        sudo systemctl restart apache2

#Install Extentions

        sudo apt-get install php7.2-mbstring
        sudo apt-get install php7.2-xml
