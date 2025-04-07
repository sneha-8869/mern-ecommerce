# Annapurna Store - MERN E-commerce

A full-featured e-commerce platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- User Authentication (Login/Register)
- Product Catalog with Categories
- Shopping Cart Management
- Wishlist Functionality
- Order Processing & Tracking
- Secure Payment Integration (Stripe)
- Admin Dashboard
- Responsive Design

## Tech Stack

### Frontend
- React.js
- Redux for state management
- Tailwind CSS for styling
- Axios for API requests

### Backend
- Node.js & Express.js
- MongoDB with Mongoose
- JWT for authentication
- Cloudinary for image storage
- Stripe for payments

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/sneha-8869/mern-ecommerce.git
cd mern-ecommerce
```

2. Install Backend Dependencies
```bash
cd backend
npm install
```

3. Install Frontend Dependencies
```bash
cd frontend
npm install
```

4. Set up environment variables:

Create a .env file in the backend directory with:
```
MONGODB_URL=your_mongodb_url
JWT_SECRET=your_jwt_secret
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret
CLOUDINARY_NAME=your_cloudinary_name
STRIPE_SECRET_KEY=your_stripe_secret_key
```

5. Start the servers:

Backend:
```bash
cd backend
npm start
```

Frontend:
```bash
cd frontend
npm run dev
```

## Features in Detail

### User Features
- User registration and login
- Browse products by category
- Add/remove items to/from cart
- Add/remove items to/from wishlist
- Place orders and track status
- View order history
- Secure payment processing

### Admin Features
- Product management (Add/Edit/Delete)
- Order management
- User management
- Sales analytics
- Inventory management

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Sneha - [sneha2k05@gmail.com]
Project Link: https://github.com/sneha-8869/mern-ecommerce