## Project Author:

https://github.com/LaravelDaily/Livewire-Parent-Child-Master-Detail
https://www.youtube.com/watch?v=iuIEqOcQi6g

I am using this projec to learn about multistep forms with livewire.

## My Notes:

https://devmarketer.io/learn/setup-laravel-project-cloned-github-com/
https://stackoverflow.com/questions/38437072/setup-laravel-project-after-cloning
php artisan key:generate
composer install
npm install
create empty database, update .env and then run mingrations: php artisan migrate

If migrations fail:
https://stackoverflow.com/questions/10169960/mysql-error-1449-the-user-specified-as-a-definer-does-not-exist

https://stackoverflow.com/questions/64841185/error-1356-hy000-view-mysql-user-references-invalid-tables-or-columns-o
Create/drop users as opposed to altering them.

mysq -u root -p
SELECT User, Host FROM SELECT User, Host,

If the user is missing create a new one.

CREATE USER 'newuser'@'localhost' IDENTIFIED BY 'password'; IDENTIFIED BY 'password';

Without password:
CREATE USER 'newuser'@'localhost';

To delete a user:
DROP USER 'username'@'host';

SHOW DATABASES;

## livewire

Use livewire to make form dynamic.

composer require livewire/livewire
php artisan make: livewire Products

move form into livewire component
