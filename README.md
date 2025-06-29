# 🛍️ ECommerce_MERN

A full-stack e-commerce application built using the MERN (MongoDB, Express, React, Node) stack. Features product listings, shopping cart, user authentication, order processing, and an admin dashboard.

## 🎯 Features

- **User Authentication** with JWT (signup/login/logout)
- **Browse Products** (list, search, filter)
- **Detailed Product Page**
- **Shopping Cart** (add/remove items with quantity)
- **Checkout Process** (Stripe integration or mock flow)
- **Order History** for authenticated users
- **Admin Dashboard**:
  - CRUD operations for products
  - View/manage user accounts
  - Track and update orders
- **Responsive UI** powered by React (and optional UI library)
- **API** built with Express & MongoDB

## 🛠️ Tech Stack

- **Backend**: Node.js, Express, MongoDB (Mongoose)
- **Frontend**: React, Redux (or Context API), CSS/Bootstrap/Tailwind
- **Authentication**: JSON Web Tokens (JWT)
- **Payment**: Stripe (or mock)
- **Hosting/Deployment**:
  - Backend: Heroku/AWS/DigitalOcean
  - Frontend: Netlify/Vercel

## 📂 Project Structure

\`\`\`
ECommerce_MERN/
├── backend/
│   ├── controllers/       # API endpoints
│   ├── models/            # MongoDB schemas
│   ├── routes/            # Express routes
│   ├── middleware/        # Auth & error handling
│   ├── config/            # DB connection, env variables
│   ├── server.js          # Entry point
├── frontend/
│   ├── public/            # Static assets
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Route-based pages
│   │   ├── store/         # Redux slices (if used)
│   │   ├── utils/         # Helpers (API calls, constants)
│   └── package.json
├── .env.example
├── package.json
└── README.md
\`\`\`

## 🔧 Setup & Installation

### Backend

\`\`\`bash
cd backend
npm install
cp .env.example .env
# Set MONGO_URI, JWT_SECRET, STRIPE_KEY, etc.
npm run dev
\`\`\`

### Frontend

\`\`\`bash
cd frontend
npm install
npm start
\`\`\`

Your app should be running:
- Frontend at `http://localhost:3000`
- Backend at `http://localhost:5000`

## 🏗 Usage

1. Browse products on home page  
2. Sign up or log in to shop  
3. Add products to your cart  
4. Proceed to checkout and place order  
5. View past orders in profile  
6. (Admin) Log in as admin to add/edit/delete products or manage orders  

## 🧪 Testing

\`\`\`bash
cd backend
npm test
cd ../frontend
npm test
\`\`\`

## 📫 Contact

Created by **Neeraj Kondaveeti**  
Reach me at: neerajkondaveeti1901@gmail.com

## 📌 Roadmap / To‑Do

- ✅ Stripe payment integration  
- ✅ Admin dashboard enhancements  
- 🔄 Product search & filtering improvements  
- 📦 Image upload (Cloudinary/S3)  
- 🧾 Email notifications (order confirmations)  
- 🔐 OAuth login (Google, Facebook)  
- 📱 Mobile UI optimizations  
