## Author
Nayan Prajapati

## Overview
This repository contains the source code for a full-fledged e-commerce website built using the MERN stack (MongoDB, Express, React, Node.js). 
The application features a fully functional online store with user authentication, product management, cart functionality, and order processing.

## Features

User Authentication and Authorization
Product Listing and Management
Shopping Cart
Order Management
Payment Integration
Responsive Design
Tech Stack
Frontend: React, Redux, CSS, Bootstrap
Backend: Node.js, Express.js
Database: MongoDB
Payment Gateway: Braintree

## Installation
Prerequisites
Make sure you have the following installed on your local machine:

Node.js
MongoDB
npm or yarn

##Clone the Repository
bash
Copy code
git clone https://github.com/Naynn2003/ecommerce.git

cd ecommerce
Install Dependencies

## Backend
bash
Copy code

## cd backend
npm install

Frontend
bash
Copy code
cd ../frontend
npm install
Configuration
Backend

Create a .env file in the backend directory and add the following environment variables:

makefile
Copy code


PORT=5000
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>
STRIPE_SECRET_KEY=<Your Stripe Secret Key>
Frontend
Create a .env file in the frontend directory and add the following environment variable:

vbnet
Copy code
REACT_APP_BRAINTREE_PUBLIC_KEY=<Your Stripe Public Key>
Running the Application
Backend
bash
Copy code
cd backend
npm run dev
Frontend
bash
Copy code
cd frontend
npm start
The backend server will be running on http://localhost:5000 and the frontend on http://localhost:3000.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.
