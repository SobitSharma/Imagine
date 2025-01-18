# Image selling application with ImageKit, Razorpay and NextAuth.

# Features:
 - User authentication with NextAuth
 - Image upload with [Imagine](https://imagekit.io)
 - Payment processing with Razorpay
 - Product management with CRUD operations

# Technologies:
 - Next.js
 - React
 - Tailwind CSS
 - ImageKit
 - Razorpay
 - NextAuth

# Installation:
 1. Clone the repository
 2. Install dependencies:npm install
 3. Start the development server: npm run dev

# Usage:
 1. Run the development server: npm run dev
 2. Open the application in your browser at http://localhost:3000

#Create a .env file with the following configurations as given below

# MongoDB Configuration
MONGODB_URI=

# Authentication
NEXTAUTH_SECRET=

# ImageKit Configuration
NEXT_PUBLIC_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
NEXT_PUBLIC_URL_ENDPOINT=

# Razorpay Configuration
RAZORPAY_KEY_ID=your_razorpay_key_id_here
RAZORPAY_KEY_SECRET=your_razorpay_secret_here
RAZORPAY_WEBHOOK_SECRET=your_razorpay_webhook_secret_here

# Mailtrap Configuration
MAILTRAP_HOST=sandbox.smtp.mailtrap.io
MAILTRAP_PORT=2525
MAILTRAP_USER=your_mailtrap_user_here
MAILTRAP_PASS=your_mailtrap_password_here
