### Laravel Coding Test: Customer Search Functionality

**Installation:**

1- Clone the Repositor<br />
git clone https://github.com/yasir-sherwani99/laravel-code-test.git
<br /><br />
2- Install Composer Dependencies
composer install

3- Setup .env
Duplicate the .env.example file and rename it to .env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password

4- Generate an application key
php artisan key:generate

5- Migrate the Database
php artisan migrate

6- Seed the Database
php artisan db:seed

7- Start the Development Server
php artisan serve

**Task Description:**

There are 5 models involved:
1- Customer
2- Product
3- Order
4- OrderItem
5- OrderAddress

### Requirements:

1. **Create a Customer Listing:** Implement functionality to list all customers along with their associated orders and items.

2. **Implement a Search Feature:** Add a search option that allows users to search for customers based on:
    - Customer email
    - Order number
    - Item name

3. **Filter the Results:** The search results should filter the customers based on the search criteria provided. Ensure that the search functionality works efficiently and returns relevant results based on the input.

4. **Ensure Efficient Queries:** Consider the impact of your implementation on performance, especially regarding database queries. Your solution should be optimized to avoid unnecessary database calls and should handle large datasets efficiently.

5. **Document Your Approach:** Write a brief explanation (200 words or less) describing how you implemented the search functionality and any considerations you took into account to optimize performance.

**Deliverables:**

- The implemented search functionality.
- A brief explanation of your approach and how you optimized the search.

**Evaluation Criteria:**

- Effective implementation of the search functionality across multiple related models.
- Proper use of Eloquent relationships and query optimization techniques.
- Code clarity and maintainability.
- Consideration for scalability and performance.

**Submission:**
Submit your code and explanation via email or through a GitHub repository link.

---
f
This test is designed to evaluate your ability to implement complex search functionality in Laravel, optimizing for performance and adhering to best practices.


Create a branch with your name and submit your code in a pull request.
