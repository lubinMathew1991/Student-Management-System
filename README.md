Installation setup
clone the project to the webserver project direcctory

rename .env.example to .env
create a DB and update DB details in .env file
run composer install
run php artisan migrate
run php artisan db:seed
run php artisan optimize
run npm install
run npm run dev
run npm run watch 10 php artisan serve
open in browser http://127.0.0.1:8000/students
