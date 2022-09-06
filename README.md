
Database tables
------------
* users (default + role)
* posts (id, author, title, body, slug, published_on, last_modified, active)
* comments (id, on_post, from_user, body, at_time

How to create the databse

use xamp or wamp to create the database and the table

* Edit the .env.example file to match your database and rename to .env
  * Set up and run the migrations i.e. php artisan migrate
 * run `composer install` and `npm install`
 *run php artisan serve



 simple Blog applicatoin in laravel
------------
what is application?
* It is simple blogging app.
* users can login/register
* users can write/update blogs
* users can read blogs
* users can comment on blogs
