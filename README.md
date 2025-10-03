# AI Powered LMS Website (MERN Stack)

This project is an **AI-powered Learning Management System (LMS)** built using the MERN stack. 
It includes features like AI course search, Google authentication, Razorpay integration for payments, 
and a powerful admin panel for managing courses and users.

---

## 🚀 Features

- AI-powered course search
- Google Authentication (OAuth)
- Razorpay integration for secure payments
- Student & Educator roles
- Create, edit, and manage courses
- Add and manage lectures (video, text, resources)
- Protected lectures (only accessible after login)
- Redux Toolkit for state management
- Responsive design with Tailwind CSS
- Admin panel for managing users and courses

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Redux Toolkit, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** Google Auth, JWT, Bcrypt
- **Payments:** Razorpay
- **AI Search:** Integrated AI-based course recommendation & search system

---

## 📂 Project Structure

- `/client` → Frontend (React + Tailwind + Redux)
- `/server` → Backend (Express + MongoDB + Auth + Payments)

---

## ⚡ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-powered-lms.git
   cd ai-powered-lms
   ```

2. Install dependencies for client and server:
   ```bash
   cd client && npm install
   cd ../server && npm install
   ```

3. Setup environment variables in `.env` file (for both client & server):
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   RAZORPAY_KEY=your_razorpay_key
   RAZORPAY_SECRET=your_razorpay_secret
   ```

4. Run the project:
   ```bash
   cd server && npm run dev
   cd client && npm start
   ```

---

## 🎯 Usage

- Students can **browse courses, search with AI, and enroll**.
- Educators can **create and manage courses**.
- Admin can **manage all users and courses**.

---

## 📌 Future Improvements

- AI chatbot for learning assistance
- Real-time discussions with WebSockets
- Advanced analytics dashboard
- Video streaming optimization

---

## 👨‍💻 Author

Developed with ❤️ using MERN stack.

