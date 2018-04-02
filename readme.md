Freelancemarket, practice project.

To launch this project locally:
- git clone this repo to your local machine
- set your db configurations in .env file
- run docker-compose up --build in the project's root
- in a parallel terminal/console window, run "docker exec freelancemarket php artisan migrate && docker exec freelancemarket php artisan passport:install"
