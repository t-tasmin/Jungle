# Jungle

A mini e-commerce application built with Rails 4.2 for purposes of teaching Rails by example.

### Main view
![Main](https://github.com/t-tasmin/Jungle/blob/master/docs/main.jpg)

### Product Details
![Details](https://github.com/t-tasmin/Jungle/blob/master/docs/product_details.jpg)

### Product by Category
![Product By Category](https://github.com/t-tasmin/Jungle/blob/master/docs/categories.jpg)

### Admin Menu
![Admin](https://github.com/t-tasmin/Jungle/blob/master/docs/admin.jpg)

### Admin: All Categories
![Admin - All Categories](https://github.com/t-tasmin/Jungle/blob/master/docs/admin_all_categories.jpg)

### Admin: Addition of a new Category
![new category](https://github.com/t-tasmin/Jungle/blob/master/docs/admin_new_category.jpg)
![added category](https://github.com/t-tasmin/Jungle/blob/master/docs/admin_new_category_added.jpg)

### Admin: Addition of a new Product
![new product](https://github.com/t-tasmin/Jungle/blob/master/docs/admin_new_product.jpg)

### Admin: Addition of a new Sale
![new sale](https://github.com/t-tasmin/Jungle/blob/master/docs/admin_sale.jpg)

### Registration
![sign-up](https://github.com/t-tasmin/Jungle/blob/master/docs/sign_up.jpg)

### Login
![lgin](https://github.com/t-tasmin/Jungle/blob/master/docs/login.jpg)

### Cart
![cart](https://github.com/t-tasmin/Jungle/blob/master/docs/my_cart.jpg)

### Final Order
![Final Order](https://github.com/t-tasmin/Jungle/blob/master/docs/final_order.jpg)





## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe
