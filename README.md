To run this project you will need a complete PHP and nodeJS environment in machine.
Maybe docker is a great choice to avoid undesirable changes on your main operating system

after clone this repo, in terminal paste the code ahead:

composer install; npm install; cp .env.example .env; touch database/database.sqlite; php artisan migrate; php artisan key:generate;
