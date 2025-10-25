# BiteBuddy - Food Ordering Website

This repository hosts the source code for BiteBuddy, a modern food ordering platform built with the MERN Stack. It offers a user-friendly interface for seamless online food ordering and delivery.

## Demo

## Features

* User Panel
* Admin Panel
* JWT Authentication
* Password Hashing with Bcrypt
* Stripe Payment Integration
* Login/Signup
* Logout
* Add to Cart
* Place Order
* Order Management
* Products Management
* Filter Food Products
* Login/Signup
* Authenticated APIs
* REST APIs
* Role-Based Identification
* Beautiful Alerts

## Run Locally

Clone the project

```bash
git clone https://github.com/Mshandev/Food-Delivery
```

Go to the project directory

```bash
cd Food-Delivery
```

Install dependencies (frontend)

```bash
cd frontend
npm install
```

Install dependencies (admin)

```bash
cd admin
npm install
```

Install dependencies (backend)

```bash
cd backend
npm install
```

Setup Environment Variables

```
Make .env file in "backend" folder and store environment Variables  
  JWT_SECRET=YOUR_SECRET_TEXT  
  SALT=YOUR_SALT_VALUE  
  MONGO_URL=YOUR_DATABASE_URL  
  STRIPE_SECRET_KEY=YOUR_KEY  
```

Setup the Frontend and Backend URL

* **App.jsx** in Admin folder

  ```js
  const url = YOUR_BACKEND_URL
  ```
* **StoreContext.js** in Frontend folder

  ```js
  const url = YOUR_BACKEND_URL
  ```
* **orderController** in Backend folder

  ```js
  const frontend_url = YOUR_FRONTEND_URL
  ```

Start the Backend server

```bash
nodemon server.js
```

Start the Frontend server

```bash
npm start
```

Start the Admin server

```bash
npm start
```

## Tech Stack

* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/en)
* [Express.js](https://expressjs.com/)
* [Mongodb](https://www.mongodb.com/)
* [Stripe](https://stripe.com/)
* [JWT-Authentication](https://jwt.io/introduction)
* [Multer](https://www.npmjs.com/package/multer)


