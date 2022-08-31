# Install Symfony CLI
 wget https://get.symfony.com/cli/installer -O - | bash

## Start Symfony

symfony server:start

# Start React watch changes: 

yarn encore dev --watch

# Run 
http://127.0.0.1:8000/

# Create Database: 
	
php bin/console doctrine:database:create

# Create User Mysql:

CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost';
flush privileges;

# Create Migration: 

php bin/console make:migration

# Execute Migration:

php bin/console doctrine:migrations:migrate

# Create Controller:

php bin/console make:controller ProjectController


