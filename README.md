# How to use


Clone repo

	git clone https://github.com/webdevmatics/webdevforum.git
Install the composer dependencies

	composer install
	
Save .env.example as .env and put your database credentials

Set application key

	php artisan key:generate        

And Migrate with

`php artisan migrate`

npm run developer

You must put at least one tag in database tags table, in order to create(post) a Thread. 
Write a comment on that Thread and you will see a new notification on navbar.

