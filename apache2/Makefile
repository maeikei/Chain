
.PHONY : all

all:
	sudo cp -rf ./ports.conf /etc/apache2/ports.conf
	sudo cp -rf ./sites-available/*.conf /etc/apache2/sites-available/
	sudo cp -f ./php5/apache2/php.ini /etc/php5/apache2/
	sudo service apache2 restart

