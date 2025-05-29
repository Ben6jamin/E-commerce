# E-commerce Web Application

A full-stack E-commerce platform built with React, Node.js, and MongoDB.

## Features

- User Authentication (Login/Signup)
- Product Catalog with Search and Filtering
- Shopping Cart Functionality
- Secure Payment Processing with Stripe
- Order Management
- Responsive Design
- User Profile Management

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Payment**: Stripe
- **State Management**: Redux Toolkit

## Project Structure

```
e-commerce/
├── client/                 # React frontend
├── server/                 # Node.js backend
├── .gitignore
└── README.md
```

## Setup Instructions

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Backend Setup

1. Navigate to the server directory:
   ```bash
   cd server
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a .env file with the following variables:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. Start the server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the client directory:
   ```bash
   cd client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a .env file with the following variables:
   ```
   REACT_APP_API_URL=http://localhost:5000
   REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
   ```

4. Start the development server:
   ```bash
   npm start
   ```

## API Endpoints

- POST /api/auth/register - User registration
- POST /api/auth/login - User login
- GET /api/products - Get all products
- GET /api/products/:id - Get single product
- POST /api/orders - Create order
- GET /api/orders - Get user orders

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request