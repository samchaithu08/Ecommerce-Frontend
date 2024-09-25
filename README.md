# Full Stack eCommerce Website

This project is a **Full Stack eCommerce website** built using the **MERN stack** (MongoDB, Express, React, and Node.js). It allows users to browse products, add items to the cart, choose product variants (such as size), and place orders using either **Cash on Delivery** or **Online Payment** methods (integrating **Stripe** and **Razorpay**).

## Features

- **Product Browsing**: Users can explore products, filter and sort them, and view detailed information about each item.
- **Cart Functionality**: Add products to the cart, select variants, and adjust quantities.
- **Checkout Process**: Users can place orders by entering a delivery address and choosing a payment method.
  - **Payment Options**: Cash on Delivery or Online Payment via **Stripe** and **Razorpay**.
- **Admin Dashboard**: Manage products by adding new items, editing existing ones, and deleting products from the store.
- **Backend**: Built using **Node.js** and **Express.js**, with product, user, and order data stored in **MongoDB**.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payment Integration**: Stripe and Razorpay
- **Deployment**: Vercel (Frontend) and possibly services like Heroku or Render for the backend.

## Installation and Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/samchaithu08/ecommerce-website.git
   cd ecommerce-website
   ```

2. **Install dependencies for both frontend and backend**
   - Navigate to the `frontend` and `backend` directories and run:
   ```bash
   npm install
   ```

3. **Start the development servers**
   - For the frontend:
   ```bash
   cd frontend
   npm start
   ```
   - For the backend:
   ```bash
   cd backend
   npm start
   ```

4. **Configure environment variables**
   - Set up the required environment variables for database connection, Stripe, and Razorpay API keys in the `.env` file.

5. **Deploy the application**
   - Once the project is ready, you can deploy it on platforms like **Vercel** (for the frontend) and **Heroku** or **Render** (for the backend).

## Features Breakdown

- **User Features**:
  - Browse products and apply filters/sorting.
  - Add products to the cart and proceed to checkout.
  - Place orders and choose from multiple payment options.

- **Admin Features**:
  - Manage product listings via the admin dashboard.
  - Add new products, edit or delete existing products.
