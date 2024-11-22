# Zephyr - Real-Time Chat Application

Zephyr is a feature-rich, real-time chat application designed to provide instant communication and seamless interaction between users. Built using modern technologies, it emphasizes scalability, reliability, and security.

## 🌟 Features

- **Real-Time Messaging**: Instant communication powered by **Socket.IO**.
- **User Authentication**: Secure authentication with **JWT** and encrypted passwords using **bcrypt.js**.
- **State Management**: Lightweight and efficient state handling with **Zustand**.
- **Dynamic Routing**: Navigation handled seamlessly with **React Router**.
- **Notifications**: Instant feedback with **React Hot Toast**.
- **Caching and Streaming**: Efficient message handling using **Redis** and **Upstash Kafka**.
- **Responsive Design**: Styled with **Tailwind CSS** and enhanced with **DaisyUI**.
- **Database**: Robust data management using **MongoDB** and **Mongoose**.

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework**: React.js with Vite for fast development.
- **State Management**: Zustand.
- **Styling**: Tailwind CSS, DaisyUI, and Lucide React.
- **Notifications**: React Hot Toast.
- **Real-Time Communication**: Socket.IO Client.
- **Routing**: React Router.

### **Backend**
- **Server Framework**: Express.js.
- **Language**: JavaScript (with ES Modules).
- **Real-Time Communication**: Socket.IO.
- **Authentication**: JSON Web Tokens (JWT) and bcrypt.js.
- **Database**: MongoDB, managed with Mongoose.
- **Configuration**: dotenv for environment variables.
- **Cross-Origin Requests**: CORS middleware.
- **File Uploads**: Cloudinary (for managing uploaded assets).

### **Development Tools**
- **Frontend**: Vite for blazing-fast bundling.
- **Backend**: Nodemon for automatic server reloading.
- **Linting**: ESLint for consistent and clean code.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- **Node.js**: v16 or above
- **MongoDB**: Running locally or a cloud instance (e.g., MongoDB Atlas)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya-040/Zephry.git
   cd Zephyr
2.Install dependencies for both frontend and backend:
```bash
cd frontend
npm install
cd ../backend
npm install
```
3.Create a .env file in the backend directory and add the following:
```bash
PORT=5000
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret
```
##Running the application

1.Start backend
```bash
cd backend
npm run dev
```
2.Start frontend
```bash
cd frontend
npm run dev



