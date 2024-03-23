# E-commerce Website
This project is a fully functional e-commerce platform where users can browse products, add them to their cart, and complete purchases. It includes features such as user authentication, product search, filtering, and payment integration.

Features
User Authentication: Users can create accounts, log in, and log out. Authentication is implemented using JSON Web Tokens (JWT) for secure access to user-specific features and data.

Product Catalog: The website displays a catalog of products with details such as name, description, price, and images. Users can browse products by category and search for specific items.

Shopping Cart: Users can add products to their shopping cart, adjust quantities, and remove items. The shopping cart is persistent across sessions, allowing users to continue shopping from where they left off.

Checkout Process: Users can proceed to checkout from their shopping cart, where they enter shipping and payment information. Payment integration is implemented using the Stripe API for secure and seamless transactions.

Order History: Registered users have access to their order history, where they can view details of past purchases, including order date, products, quantities, and total amount.

Technologies Used
Frontend: The frontend of the website is built using React, a popular JavaScript library for building user interfaces. Additional libraries and frameworks include React Router for client-side routing, Redux for state management, and Material-UI for styling components.

Backend: The backend of the website is built using Node.js, a server-side JavaScript runtime, and Express.js, a web application framework for Node.js. Data is stored in a PostgreSQL database using Sequelize, an ORM (Object-Relational Mapping) library for Node.js.

Authentication: User authentication is implemented using JSON Web Tokens (JWT) and bcrypt for secure password hashing. Sessions are managed using HTTP cookies for persistent login sessions.

Payment Integration: Payment integration is achieved using the Stripe API, which provides a secure and easy-to-use platform for processing online payments. Users can securely enter their payment information and complete transactions without leaving the website.
