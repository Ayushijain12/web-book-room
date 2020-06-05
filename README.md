# web-book-roomHere are the steps which need to be performed for setup and run project.

Steps for Laravel setup and run : Backend 

Clone the given repository of the project
Run the Command : composer install 
Start Migration process using migration command : php artisan migrate --seed
Install passport using this command : php artisan passport:instal --force 
Now check your database which has stored rooms and users details. 
Please go through this link https://www.getpostman.com/collections/003c884eb489b2fd7945 which has all the API Postman collections.. 
Set your environment using your local url.
Run the project using this command : php artisan serve
Note : Make sure you have an .env and .env.example file in your project while you clone the project using repository as because github doesn’t commit/push/pull .env .env.example file.


I know about the saga and commands for the same but never implement saga. So here I am using thunk instead of saga.
Steps for React setup and run : Frontend 




