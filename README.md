# 🚀 Lets Chat - Real-Time Chat Application  

A modern, full-stack real-time messaging application built with MERN stack & Socket.io for seamless communication.  

## 🌟 Overview  
Lets Chat enables users to exchange messages in real-time with **secure authentication**, **dynamic online tracking**, and **cloud-based media storage**.  

### ✨ Features  
- 🔒 **Authentication & Authorization** – Secure login with JWT  
- 💬 **Real-Time Messaging** – Instant chat powered by Socket.io  
- 👥 **Online Status Tracking** – Presence detection for active users  
- 📸 **Cloud-Based Image Storage** – Upload & serve media via Cloudinary  
- 🌍 **Global State Management** – Efficient state handling using Zustand  
- 🚀 **Optimized Backend** – Robust API integration with error-handling middleware  
- 🖌️ **Responsive UI & Animations** – Styled with Tailwind CSS & Daisy UI  

## 🔧 Tech Stack  
| Technology | Role |
|------------|------|
| MongoDB | NoSQL database for chat storage |
| Express.js | Backend framework for API & authentication |
| React.js | Frontend UI components |
| Node.js | Handles API interactions & business logic |
| Socket.io | Enables real-time communication |
| Cloudinary | Image storage & delivery optimization |
| JWT | Secure authentication & session management |
| Zustand | Lightweight state management |

## 🚀 Setup & Installation  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/ShivdasJadhav/lets_chat.git
cd lets_chat
```
### 2️⃣ Configure Environment Variables
Create a .env file in server dir and add the following:

```sh
MONGODB_URI=your-mongodb-uri
PORT=5001
JWT_SECRET=your-secret-key
CLOUDINARY_CLOUD_NAME=your-cloud-name
CLOUDINARY_API_KEY=your-api-key
CLOUDINARY_API_SECRET=your-api-secret
NODE_ENV=development
```

### 3️⃣ Install Dependencies
for the both folders client and the server
```sh
npm install
/*It will ake necessary installation of packages and dependencies*/
```