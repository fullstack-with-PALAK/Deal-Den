# DealDen

A feature-rich online marketplace built with the MERN stack (MongoDB, Express, React, Node.js). DealDen enables users to buy and sell products, manage shops, and participate in real-time auctions.

## Features

### User Management
- User registration and authentication
- Profile management with secure password handling
- JWT-based session management

### Multi-Vendor Marketplace
- Create and manage multiple shops
- Product catalog with categories
- Image upload support for products
- Search and filter products

### Shopping Cart & Checkout
- Add products to cart from multiple shops
- Stripe payment integration
- Order tracking and history

### Real-Time Auctions
- Create and manage auctions
- Real-time bidding system
- Countdown timer for auction end times
- Bid history tracking

### Seller Dashboard
- Shop performance analytics
- Order management
- Product inventory control
- Stripe Connect for seller payments

## Tech Stack

- **Frontend:** React 16, Material-UI, React Router
- **Backend:** Node.js, Express
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT with express-jwt
- **Payments:** Stripe Connect & Checkout
- **Build Tools:** Webpack, Babel, Nodemon

## Getting Started

### Prerequisites
- Node.js (v13+)
- MongoDB
- Stripe account (for payment features)

### Installation

1. Clone the repository
```bash
git clone https://github.com/fullstack-with-PALAK/Deal-Den.git
cd Deal-Den
```

2. Install dependencies
```bash
npm install
```

3. Configure environment variables in `config/config.js`:
- MongoDB URI
- JWT secret
- Stripe API keys

4. Start the development server
```bash
npm run development
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Scripts

- `npm run development` - Start development server with hot reloading
- `npm run build` - Build for production
- `npm run start` - Start production server

## Project Structure

```
├── client/                 # React frontend
│   ├── auth/              # Authentication components
│   ├── auction/           # Auction system
│   ├── cart/              # Shopping cart
│   ├── core/              # Core components (Home, Menu)
│   ├── order/             # Order management
│   ├── product/           # Product components
│   ├── shop/              # Shop management
│   └── user/              # User profile
├── server/                 # Express backend
│   ├── controllers/       # Route controllers
│   ├── models/            # Mongoose models
│   ├── routes/            # API routes
│   └── helpers/           # Utility functions
└── config/                 # Configuration files
```

## License

MIT License - see [LICENSE.md](LICENSE.md) for details

## Author

**Palak** - Full Stack Developer
