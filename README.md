<div align="center">

# 🎓 Learning Management System (LMS)

A modern, full-stack e-learning platform built with the MERN stack


<br /><hr /><br />

<div align="center">


## 🌟 Features

### For Students
- 📚 Browse and enroll in various courses
- 💳 Secure payment processing with Stripe
- 📝 Track learning progress
- ⭐ Rate and review courses
- 👤 Personalized user dashboard
- 🎯 Access to enrolled course content

### For Educators
- 📝 Create and manage courses
- 📊 Track student enrollments
- 💰 Manage course pricing and discounts
- 📈 View analytics and earnings
- 🖼️ Upload course thumbnails via Cloudinary
- 📹 Organize course content and materials

### General Features
- 🔐 Secure authentication with Clerk
- 💫 Modern and responsive UI
- 🌐 Real-time updates
- 📱 Mobile-friendly design
- 🔍 Advanced course search and filtering
- 🎨 Beautiful course cards and layout

## 🛠️ Technology Stack

### Frontend
- React.js with Vite for fast development
- React Router for navigation
- Tailwind CSS for styling
- Clerk for authentication UI components
- Stripe Elements for payment UI

### Backend
- Node.js & Express.js
- MongoDB with Mongoose ODM
- Clerk for user authentication
- Cloudinary for image management
- Stripe for payment processing

### Security Features
- JWT token authentication
- Secure webhook handling
- Environment variable protection
- Input validation and sanitization

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Clerk Account
- Stripe Account
- Cloudinary Account

### Installation

1. Clone the repository
```bash
git clone https://github.com/elyse502/lms.git
cd lms
```

2. Install dependencies
```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. Set up environment variables

Create `.env` files in both client and server directories:

```env
# Server .env
PORT=5000
MONGODB_URI=your_mongodb_uri
CLERK_SECRET_KEY=your_clerk_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
```

```env
# Client .env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
```

4. Start the application
```bash
# Start backend server
cd server
npm run start

# Start frontend in a new terminal
cd client
npm run dev
```

## 📱 Application Structure

```
lms/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/        # Page components
│   │   ├── context/      # React context providers
│   │   └── utils/        # Utility functions
│   └── public/           # Static assets
└── server/               # Backend Node.js application
    ├── configs/          # Configuration files
    ├── controllers/      # Request handlers
    ├── models/          # MongoDB models
    ├── routes/          # API routes
    └── utils/           # Helper functions
```

## 🔒 Security

- Authentication handled by Clerk
- Secure payment processing with Stripe
- Protected API endpoints
- Secure file uploads with Cloudinary
- Input validation and sanitization
- Protected environment variables

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.




