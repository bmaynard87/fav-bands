# My Favorite Bands
A simple SPA to demostrate Laravel and Angular proficiency. Also includes a few other technologies, such as Bootstrap, SASS, Gulp, and Node.

## Setup
1. `git clone https://github.com/bmmaynard87/favbands.git`
2. `cd favbands`
3. `composer install`
4. `php artisan key:generate`
5.  Windows: `vendor/bin/homestead make` Mac: `php vendor/bin/homestead make`
6. `vagrant up` 
7. `vagrant ssh`
8. `cd ~/Code/favbands`
9. `php artisan migrate`
10. `php artisan db:seed`
11. Ready to go! Navigate to http://192.168.10.10 in your browser