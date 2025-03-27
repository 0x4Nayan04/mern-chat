# Chatty - Realtime MERN Chat Application

A full-stack real-time chat application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and Socket.IO.

![Chatty App Banner](https://i.imgur.com/placeholder-image.jpg)

## ✨ Features

- **Real-time Messaging** using Socket.IO
- **Authentication** (Login/Signup)
- **Responsive Design** for all devices
- **Online Status Indicators**
- **Image Sharing** in messages
- **Profile Customization**
- **Theme Selection** with 32+ themes
- **Message History**
- **Avatar Upload** using Cloudinary

## 🚀 Tech Stack

- **Frontend**:

  - React.js with hooks
  - Zustand for state management
  - TailwindCSS with DaisyUI components
  - React Router DOM for routing
  - Axios for HTTP requests
  - Socket.IO client for real-time communication
  - React Hot Toast for notifications

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB with Mongoose
  - JWT for authentication
  - Socket.IO for real-time communication
  - Cloudinary for image storage
  - bcrypt.js for password hashing

## 📦 Installation & Setup

### Prerequisites

- Node.js (v14+ recommended)
- MongoDB database
- Cloudinary account for image storage

### Environment Variables

Create a `.env` file in the backend directory with:

```
MONGO_URI=<your_mongo_db_uri>
JWT_SECRET=<your_jwt_secret>
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
```

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/chatty.git
   cd chatty
   ```

2. Install dependencies for both frontend and backend:

   ```sh
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

3. Start the development server:
   ```sh
   cd backend
   npm run dev
   cd ../frontend
   npm start
   ```

### Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Sign up for a new account or log in with an existing account.
3. Start chatting with your friends in real-time!

## 📂 Folder Structure

```
chatty/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── .env
│   ├── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   ├── .env
│   ├── package.json
```

## 📋 API Endpoints

### Auth

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Log in a user

### Messages

- `GET /api/messages` - Get all messages
- `POST /api/messages` - Send a new message

### Users

- `GET /api/users` - Get all users
- `GET /api/users/:id` - Get a user by ID

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For any inquiries, please contact [your-email@example.com](mailto:your-email@example.com).
