# VibeCare - Healthcare Appointment System

A full-stack healthcare appointment booking platform with separate frontend, backend, and admin interfaces.

## 🚀 Features

- User authentication and authorization
- Doctor search and filtering by speciality
- Appointment scheduling and management
- Admin dashboard for system management
- Secure payment integration (Stripe & Razorpay)
- Real-time notifications
- Profile management

## 🛠️ Tech Stack

- **Frontend**: React.js, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **File Storage**: Cloudinary
- **Payment**: Stripe, Razorpay

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/MeRabah/vibecare.git
cd vibecare
```

2. Install dependencies for all parts:
```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install

# Admin
cd ../admin
npm install
```

3. Set up environment variables:
Create `.env` files in frontend, backend, and admin directories using the provided `.env.example` templates.

4. Start the development servers:
```bash
# Backend
cd backend
npm run dev

# Frontend
cd frontend
npm run dev

# Admin
cd admin
npm run dev
```

## 🌐 Environment Variables

### Backend
- `MONGODB_URI`: MongoDB connection string
- `JWT_SECRET`: Secret key for JWT
- `CLOUDINARY_NAME`: Cloudinary name
- `CLOUDINARY_API_KEY`: Cloudinary API key
- `CLOUDINARY_SECRET_KEY`: Cloudinary secret
- `STRIPE_SECRET_KEY`: Stripe secret key
- `RAZORPAY_KEY_ID`: Razorpay key ID
- `RAZORPAY_KEY_SECRET`: Razorpay secret key

### Frontend & Admin
- `VITE_BACKEND_URL`: Backend API URL
- `VITE_RAZORPAY_KEY_ID`: Razorpay public key

## 🔒 Security

- JWT authentication
- Password hashing
- Environment variables protection
- Input validation
- XSS protection

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Contact

Your Name - [@YourTwitter](https://twitter.com/YourTwitter)
Project Link: [https://github.com/MeRabah/vibecare](https://github.com/MeRabah/vibecare)
