# NodeJS - Express.js CRUD Exercise

**Goal:** Create a simple CRUD backend server using Express.js

## Instructions

1. Create a `dev` branch after accepting the assignment
2. Switch to the `dev` branch after cloning the repository to your localhost
3. Set up your Node webserver using Express. Install Express by running `npm install express` on the terminal. Set up your `tsconfig.json` and `.gitignore` files at the root of your project. The gitignore file should have `node_modules/` listed so that it does not get committed to the repository.
4. Create an empty array called `products` which will be your in-memory database. You can use the fields below for your object properties

    - id
    - product_name
    - product_description
    - product_price

6. Create the routes with the correct methods for each of the CRUD functions:

    - `/products` : GET request for all products
    - `/products` : POST request to add one product
    - `/products/:id` : GET request to fetch one product based on id
    - `/products/:id` : UPDATE request to update one product based on id
    - `/products/:id` : DELETE request to delete one product based on id

7. Start your server by compiling your TypeScript and running `nodemon index.js` if your server filename is index.js
8. Use Postman to test your API routes [https://www.postman.com/]. Create an account and download the software
9. Once your server and all your routes are working, push your changes and merge from `dev` to `master/main`
