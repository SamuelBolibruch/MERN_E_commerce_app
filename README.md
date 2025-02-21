# E-Commerce Application

This is a **complete e-commerce application** that simulates the full e-commerce process. Although not a fully functional app, it provides an extensive demo of an online shopping experience, including features such as user authentication, product browsing, shopping cart, checkout process, PayPal payment integration, and order management.

**Please note:** The images used in this project are generated from the platform [https://picsum.photos](https://picsum.photos).


## Features
- **User Authentication & Authorization**: Secure sign-up and login functionality with JWT tokens.  
- **Product Browsing & Filtering**: Users can browse products and filter them based on various parameters.
- **Shopping Cart**: Add or remove products to/from the shopping cart.  
- **Checkout Process**: Proceed from the cart to a checkout page with successful payment via PayPal.  
- **Order Confirmation**: After successful payment, an order is created and confirmed.  
- **Admin Dashboard**: Manage users, products, and orders with an admin panel.

## Screenshots

### Home Page
![Home Page](/frondend/public/e-home-full.png)

### Product Collection
![Product Collection](/frondend/public/e-collection.png)

### Product Details
![Product Details](/frondend/public/e-product-details.png)

### Login Page
![Login Page](/frondend/public/e-login.png)

### Register Page
![Register Page](/frondend/public/e-register.png)

### Shopping Cart
![Shopping Cart](/frondend/public/e-cart.png)

### Checkout Page
![Checkout Page](/frondend/public/e-checkout.png)

### PayPal Payment
![PayPal Payment](/frondend/public/e-paypal.png)

### Order Confirmation
![Order Confirmation](/frondend/public/e-order-confirmation.png)

### All Orders
![All Orders](/frondend/public/e-all-orders.png)

### Order Details
![Order Details](/frondend/public/e-order-details.png)

### Admin Panel
![Admin Panel](/frondend/public/e-admin.png)

### Admin Users Management
![Admin Users](/frondend/public/e-admin-users.png)

### Admin Products Management
![Admin Products](/frondend/public/e-admin-products.png)

### Admin Orders Management
![Admin Orders](/frondend/public/e-admin-orders.png)

## Technologies Used

### Backend
- **Node.js**: Server-side runtime environment.  
- **Express**: Fast and minimalist web framework for Node.js.  
- **MongoDB**: NoSQL database for storing user data, products, and orders.  
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB.  
- **JWT (jsonwebtoken)**: For secure token-based authentication.  
- **bcryptjs**: For secure password hashing.  
- **Cloudinary**: For media storage and management (e.g., product images).  
- **Multer**: For handling file uploads.  
- **CORS**: To enable cross-origin requests.  

### Frontend
- **React**: JavaScript library for building user interfaces.  
- **React Router**: For navigation and routing between pages.  
- **Redux Toolkit**: For managing global application state.  
- **Axios**: For making HTTP requests to the backend.  
- **React PayPal JS**: For integrating PayPal payment system.  
- **TailwindCSS**: For responsive and modern styling.  
- **Sonner**: For toast notifications.  

## Deployment
This application is deployed on **[Vercel](https://e-commerce-app-frontend-two.vercel.app)**, allowing seamless access and testing.
