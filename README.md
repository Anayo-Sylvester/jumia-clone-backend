Jumia Backend Clone 📚

Welcome to the Jumia Backend Clone! This project replicates the core functionalities of the Jumia e-commerce platform's backend, providing APIs and server-side logic for user management, product catalog, orders, and payment processing.

✨ Features

User Authentication – Sign-up, login, and secure token-based authentication.

Product Management – CRUD operations for products and categories.

Order Processing – Manage orders, cart items, and order history.

Payment Integration – Mock payment processing for transaction management.

Admin Panel – Manage users, products, and order analytics.

Search & Filters – Search products by name, category, and filters.

⚙️ Technologies Used

Node.js – Runtime environment for the server-side code.

Express.js – Web framework for building the API.

MongoDB – Database for storing user and product data.

JWT (JSON Web Tokens) – For secure user authentication.

Mongoose – ODM library for MongoDB.

Bcrypt – For password hashing.

📈 Installation

Clone this repository and navigate to the project folder:

git clone https://github.com/yourusername/jumia-backend-clone.git
cd jumia-backend-clone

Install the dependencies:

npm install

Create a .env file in the root directory and add the necessary environment variables:

MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret
PORT=3000

📝 API Endpoints

Authentication

POST /api/auth/register – Register a new user.

POST /api/auth/login – Login an existing user.

Products

GET /api/products – Retrieve a list of products.

POST /api/products – Add a new product (Admin only).

PUT /api/products/:id – Update a product (Admin only).

DELETE /api/products/:id – Delete a product (Admin only).

Orders

POST /api/orders – Create a new order.

GET /api/orders/:userId – Get orders for a specific user.

💡 Running the Project

Run the development server:

npm run dev

This will start the server on http://localhost:3000.

💎 Contribution

Feel free to fork this repository and create pull requests. If you find any issues or want to suggest improvements, open an issue on GitHub.

❤️ License

This project is licensed under the MIT License. See the LICENSE file for details.

Happy coding! 🚀

