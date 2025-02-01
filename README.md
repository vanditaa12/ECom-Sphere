# MyShop - E-commerce Website

## Overview
MyShop is a full-featured e-commerce platform designed to provide a seamless online shopping experience. This project includes functionalities such as user authentication, product management, cart operations, and secure payment integration.

## Features
- User authentication (Login/Register)
- Product listing and detailed view
- Shopping cart functionality
- Order management
- Payment gateway integration
- Admin panel for product & order management
- Responsive design for mobile and desktop

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Gateway**: Stripe/PayPal

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository**
```bash
git clone https://github.com/pawanpk87/myShop-Ecommerce-website.git
cd myShop-Ecommerce-website
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
Create a `.env` file in the root directory and add the required configurations:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PAYPAL_CLIENT_ID=your_paypal_client_id
STRIPE_SECRET_KEY=your_stripe_secret_key
```

4. **Run the development server**
```bash
npm start
```
The application should now be running at `http://localhost:3000`.

## Usage
- **Users** can browse products, add them to the cart, and proceed with checkout.
- **Admins** can manage products, view orders, and update order statuses.

## Contributing
Contributions are welcome! Feel free to fork this repository, create a feature branch, and submit a pull request.

## License
This project is licensed under the MIT License.
