Q-Sneakers

Q-Sneakers is a full-stack e-commerce application providing features for both users and admins to manage products, orders, and user accounts efficiently.

Table of Contents
Features
Setup Instructions
Running the Application
Environment Variables
Technologies Used
Features
User Features
Login/Signup User Account
Update Profile/Password User Account
Reset Password via Email using Nodemailer
Cart: Add/Remove Items, Update Quantities
Save For Later: Add/Remove Items
Wishlist: Add/Remove Items
Products Pagination (Default 8 Products Per Page)
Product Search
Product Filters Based on Category/Ratings, Price Range
Shipping Info in Session Storage
My Orders with Filters
Order Details of All Ordered Items
Order Confirmation Email with Details
Review Products
Admin Features
Admin Dashboard (Accessible only to admin roles)
Update Order Status, Delete Order
Add/Update Products
Update User Data, Delete User
List Product Reviews, Delete Review
Stock Management: Decrease product stock when shipped
Setup Instructions
Prerequisites
Node.js (v14 or above)
npm (v6 or above)
MongoDB
Cloning the Repository
Clone the repository:
bash
Copy code
git clone git@github.com:elias-soykat/q-sneakers.git
cd q-sneakers
Installing Dependencies
Navigate to the backend directory and install dependencies:

bash
Copy code
cd backend
npm install
Navigate to the frontend directory and install dependencies:

bash
Copy code
cd ../frontend
npm install
Environment Variables
Create a .env file in the backend directory and add the following environment variables:
plaintext
Copy code
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret_key
SMTP_HOST=smtp.your_email_provider.com
SMTP_PORT=your_smtp_port
SMTP_USER=your_email_address
SMTP_PASS=your_email_password
Running the Application
Backend
Start the backend server:
bash
Copy code
cd backend
npm run dev
Frontend
Build the frontend:

bash
Copy code
cd ../frontend
npm run build
Start the frontend server:

bash
Copy code
npm start


Technologies Used
Backend: Node.js, Express, MongoDB, Mongoose
Frontend: React, Redux, React Router
Authentication: JWT
Email Service: Nodemailer


</br>

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/elias-soykat/q-commerce/master/data/homepage.png" alt="mockup" /></td>
    <td><img src="https://raw.githubusercontent.com/elias-soykat/q-commerce/master/data/products.png" alt="mockups" /></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/elias-soykat/q-commerce/master/data/product.png" alt="mockup" /></td>
    <td><img src="https://raw.githubusercontent.com/elias-soykat/q-commerce/master/data/cart.png" alt="mockups" /></td>
  </tr>
</table>

</br>


