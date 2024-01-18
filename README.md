# Clothing Store
A functioning eCommerce store page with a cart you can add items to, built with JS and Express.

## How to Use
* In the CLI, run "npm run dev". The main page will be located on "localhost:3000"
* All the product, cart, and user data is stored locally with the project

## Stack
* JavaScript
  * Implementing and routing a multi-page site with a products page, cart page, and an admin page while using Express and multiple databases to track product and user data
  * Coded in persistence of cart data that survives after page refresh
  * Used a repository class to organize methods that are reused between the products, cart, and users 
* Express
  * Used Express Validator and Cookie Session to implement production-level validation and authentication to increase the page's data security 
* Node
  * Used BCrypt hashing to encrypt user passwords for all users in user database 

## Upcoming Features
- [ ] Update UI to include the user's name in the nav
- [ ] Improve UI for different screen sizes
- [ ] Add separate pages to sort the featured items into different categories (by gender and by item type)
- [ ] Add simulation of an actual checkout with a checkout page
- [ ] \(Optional) Update the product offering to be more logical
