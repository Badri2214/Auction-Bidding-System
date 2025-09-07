# Auction Bidding System

A full-stack Auction Bidding System where users can create auction items, place bids, and manage accounts. Built with **MERN stack** (MongoDB, Express, React, Node.js) with authentication and real-time bidding features.

---

## Features

- User registration and login  
- Create, update, and manage auction items  
- Place bids on auction items  
- Responsive and clean UI  

---

## Project Structure

```text
project/
├── backend/
│   ├── config/
│   │   └── db.js                  # Database configuration and connection setup
│   ├── controllers/
│   │   ├── auctionController.js   # Business logic for auction management
│   │   ├── bidController.js       # Business logic for bid management
│   │   └── userController.js     # Business logic for user management
│   ├── middleware/
│   │   └── authMiddleware.js     # Middleware for authentication
│   ├── models/
│   │   ├── AuctionItem.js         # Mongoose schema for auction items
│   │   ├── Bid.js                 # Mongoose schema for bids
│   │   └── User.js                # Mongoose schema for users
│   ├── routes/
│   │   ├── auctionRoutes.js       # API routes for auction-related requests
│   │   ├── bidRoutes.js           # API routes for bid-related requests
│   │   └── userRoutes.js          # API routes for user-related requests
│   └── server.js                  # Entry point for the backend server
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── AuctionItem.jsx    # Component for displaying auction items
│   │   │   ├── BidForm.jsx        # Component for submitting bids
│   │   │   ├── Home.jsx           # Home page component
│   │   │   ├── NavBar.jsx         # Navigation bar component
│   │   │   └── Signup.jsx         # Component for user registration
│   │   ├── contexts/
│   │   │   └── AuthContext.jsx    # Context for managing authentication state
│   │   ├── App.jsx                # Main application component
│   │   ├── index.jsx              # Entry point for the React app
│   │   └── main.jsx               # Renders the React app
│   ├── tailwind.config.js         # Tailwind CSS configuration
│   ├── vite.config.js             # Vite configuration for the frontend build
│   └── index.html                 # Main HTML file for the frontend
└── README.md                      # This file




