# Install by composer
composer install
bin/cake migrations migrate
bin/cake migrations seed

# Run application
bin/cake server
