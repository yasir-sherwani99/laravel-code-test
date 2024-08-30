### Laravel Coding Test: Customer Search Functionality

**Installation:**

1- Clone the Git Repository<br />
git clone https://github.com/yasir-sherwani99/laravel-code-test.git
<br /><br />
2- Install Composer Dependencies<br />
composer install
<br /><br />
3- Setup .env<br />
Duplicate the .env.example file and rename it to .env<br /><br />
DB_CONNECTION=mysql<br />
DB_HOST=127.0.0.1<br />
DB_PORT=3306<br />
DB_DATABASE=your_database_name<br />
DB_USERNAME=your_database_username<br />
DB_PASSWORD=your_database_password
<br /><br />
4- Generate an application key<br />
php artisan key:generate
<br /><br />
5- Migrate the Database<br />
php artisan migrate
<br /><br />
6- Seed the Database<br />
php artisan db:seed
<br /><br />
7- Start the Development Server<br />
php artisan serve

**Explanation:**

In my Laravel project for managing orders, I implemented the search functionality using Eloquent ORM. First, I set up a search form in the frontend to capture user input for various order attributes such as order ID, customer email, and product name.
<br /><br />
In the controller, I processed the search request by validating the input and constructing a dynamic query. I utilized Eloquent's whereHas and orwhereHas method to conditionally apply filters based on the presence of user input. For instance, if the user specified an order ID, the query would narrow down results to that specific ID.
<br /><br />
To optimize performance, I implemented indexing on relevant database columns such as order ID and customer email, which significantly reduced the search time. We can also add pagination to limit the number of results displayed per page, enhancing user experience and reducing server load. 
<br /><br />
Overall, the combination of Laravel’s Eloquent features and careful database design enabled quick and effective order searching.
