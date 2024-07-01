Q-Sneakers

Q-Sneakers is a full-stack e-commerce application providing features for both users and admins to manage products, orders, and user accounts efficiently.

Table of Contents

1.Features

2.Setup Instructions

3.Running the Application

4.Environment Variables

5.Technologies Used

Features

User Features

>Login/Signup User Account

>Update Profile/Password User Account

>Reset Password via Email using Nodemailer

>Cart: Add/Remove Items, Update Quantities

>Save For Later: Add/Remove Items

>Wishlist: Add/Remove Items

>Products Pagination (Default 8 Products Per Page)

>Product Search

>Product Filters Based on Category/Ratings, Price Range

>Shipping Info in Session Storage

>My Orders with Filters

>Order Details of All Ordered Items

>Order Confirmation Email with Details

>Review Products


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

Mongodb


Cloning the Repository

1.Clone the repository:


git clone git@github.com:elias-soykat/q-sneakers.git

cd q-sneakers

Installing Dependencies


2.Navigate to the backend directory and install dependencies:

cd backend

npm install

3.Navigate to the frontend directory and install dependencies:

cd ../frontend

npm install

Environment Variables

4.Create a .env file in the backend directory and add the following environment variables:


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

5.Start the backend server:

cd backend

npm run dev

Frontend

6.Build the frontend:

cd ../frontend

npm run build


7.Start the frontend server:

npm start

8.Open your browser and navigate to http://localhost:3000.

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


