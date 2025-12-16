# 🟦 Backend API

Node.js + Express REST API with MongoDB for the e-commerce platform.

## 🚀 Quick Start

```bash
npm install
npm run dev
```

## 📋 Environment Variables

Create `.env` file:

```bash
NODE_ENV=development
PORT=3000
DB_URL=<YOUR_MONGODB_URL>
CLERK_PUBLISHABLE_KEY=<YOUR_CLERK_KEY>
CLERK_SECRET_KEY=<YOUR_CLERK_SECRET>
CLOUDINARY_CLOUD_NAME=<YOUR_CLOUDINARY_NAME>
CLOUDINARY_API_KEY=<YOUR_CLOUDINARY_KEY>
CLOUDINARY_API_SECRET=<YOUR_CLOUDINARY_SECRET>
INNGEST_SIGNING_KEY=<YOUR_INNGEST_KEY>
ADMIN_EMAIL=<YOUR_ADMIN_EMAIL>
CLIENT_URL=http://localhost:5173
```

## 🛠️ Scripts

- `npm run dev` - Development server with auto-reload
- `npm start` - Production server
- `npm run seed:products` - Seed database with sample products

## 📡 API Endpoints

- `/api/products` - Product operations
- `/api/cart` - Cart management
- `/api/orders` - Order processing
- `/api/users` - User management
- `/api/admin` - Admin operations (protected)
- `/api/reviews` - Product reviews

## 🏗️ Tech Stack

- **Framework**: Express.js
- **Database**: MongoDB + Mongoose
- **Auth**: Clerk
- **Storage**: Cloudinary
- **Jobs**: Inngest