
# ForeverBuy eCommerce Website

ForeverBuy is a fully functional eCommerce platform built using the **MERN** stack. It allows users to browse, search, and purchase products online in a secure and seamless environment.

## Features

- **Product Listing**: Display a wide range of products in various categories.
- **Search Functionality**: Allows users to search for products by name, category, or other filters.
- **User Authentication**: Secure login and registration using JWT (JSON Web Tokens).
- **Shopping Cart**: Users can add products to their cart and proceed to checkout.
- **Order Management**: Customers can view order history and track their current orders.
- **Payment Integration**: Secure online payment options via Stripe/PayPal.
- **Admin Panel**: Admins can manage products, categories, and user accounts.
- **Responsive Design**: Mobile-friendly design using React and CSS for a great user experience on all devices.

## Technologies Used

- **Frontend**:
  - React.js
  - HTML
  - CSS (or Sass for styling)
  - Bootstrap / Material UI (for responsive UI)

- **Backend**:
  - Node.js with Express.js
  - MongoDB (NoSQL Database)
  - Mongoose (MongoDB ORM)

- **Authentication**:
  - JWT (JSON Web Tokens) for user authentication and session management

- **Payment Gateway**:
  - Stripe/PayPal for handling secure payments

- **Development Tools**:
  - NPM/Yarn for managing dependencies
  - Axios for making HTTP requests from React to Express API

## Setup Instructions

### Prerequisites

- Node.js and NPM installed on your local machine.
- MongoDB database running locally or MongoDB Atlas for cloud database hosting.
- Stripe/PayPal account (for payment gateway integration).

### Getting Started

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/foreverbuy.git
2. Navigate to the project directory:
   cd foreverbuy
3.Install the required dependencies for both the backend and frontend.

    *Backend Setup: Navigate to the backend directory and install dependencies:
       cd backend
       npm install
    *Frontend Setup: Navigate to the frontend directory and install dependencies:
       cd frontend
       npm install
4.Configure environment variables:

   *In the backend directory, create a .env file and add the necessary environment variables such as your MongoDB URI, JWT secret, and payment gateway credentials (Stripe or PayPal).
   *In the frontend directory, configure any environment variables such as the API base URL.
5.Start the backend server:
      npm start
6.Start the frontend server:
      npm start
7.Visit http://localhost:3000 in your browser to view the application.

Database Configuration
Ensure that your MongoDB database is running, and the connection string in your environment variables points to your local or cloud database. You can use MongoDB Atlas if you prefer a cloud solution.

Payment Integration
If you're using Stripe, follow the setup instructions in the Stripe documentation to create the necessary API keys and add them to your .env file. Similarly, for PayPal, configure the payment gateway in the backend.

Contributing
We welcome contributions! If you'd like to improve the project, please follow these steps:

Fork this repository.
Create a new branch for your feature (git checkout -b feature/your-feature).
Commit your changes (git commit -am 'Add a new feature').
Push to your branch (git push origin feature/your-feature).
Create a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any questions, feel free to reach out to us by creating an issue or contacting us at [your-email@example.com].



### Key Changes:

1. **MERN Stack Specifics**: I updated the "Technologies Used" section to highlight **MongoDB**, **Express**, **React**, and **Node.js**.
2. **Authentication**: Added **JWT** for handling user authentication.
3. **Payment Integration**: Mentioned **Stripe/PayPal** for payment gateway integration.

Make sure to update the repository URL (`https://github.com/your-username/foreverbuy.git`) and any specific instructions based on your project's setup.

Let me know if you need any more adjustments or additions!


******LIVE LINK******

https://foreverbuy.in/
