1. install MySql and Apachi (xampp/ wampp etc.)
2. Install Composer
3. Install Laravel Globally
```
composer global require "laravel/installer"        
```
4. Add composer to path .bashrc file to access laravel globally
```
cd ~
sudo nano .bashrc 
```
5. Edit environment config path file and by adding this line
```
export PATH="$PATH:$HOME/.config/composer/vendor/bin"        
```
6. Hot Reload config path
```
source ~/.bashrc        
```
7. Create a new Laravel application
```
laravel new projectName
```
8. Install missing composer packages and their dependencies
```
cd mail
composer install && composer update 
```
9. Run the application
```
php artisan serve
```
