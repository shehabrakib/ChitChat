# ChitChat 💬

**ChitChat** is a real-time chat application built with the **MERN stack**, featuring advanced functionalities like JWT authentication, live messaging with Socket.IO, notifications, image uploads, and more. Designed for seamless user experience with a beautiful UI, ChitChat combines performance, reliability, and simplicity in one package.

---

## 🌟 Features

- 🔐 **Custom JWT Authentication** – Secure login & registration without relying on third-party auth providers.  
- ⚡ **Real-time Messaging** – Powered by **Socket.IO** for instant communication.  
- 🟢 **Online/Offline Presence Indicators** – See who’s available at a glance.  
- 🔔 **Notification & Typing Sounds** – Interactive audio cues for messages & typing (with toggle).  
- 🗂️ **Image Uploads** – Upload and share images effortlessly via **Cloudinary**.  
- 🧰 **REST API** – Built with **Node.js** & **Express** for robust backend functionality.  
- 🧱 **MongoDB Data Persistence** – Store chat history, users, and media securely.  
- 🚦 **API Rate-Limiting** – Powered by **Arcjet** to prevent abuse and maintain performance.  
- 🎨 **Beautiful UI** – Modern interface with **React**, **Tailwind CSS**, and **DaisyUI**.  
- 🧠 **State Management** – Smooth and efficient state handling using **Zustand**.

---

## 💻 Tech Stack

- **Frontend:** React, Tailwind CSS, DaisyUI, Zustand  
- **Backend:** Node.js, Express, Socket.IO  
- **Database:** MongoDB  
- **Cloud Storage:** Cloudinary  
- **Authentication:** Custom JWT  
- **Other Tools:** Arcjet for rate-limiting  

---


## 🚀 Installation & Setup

## 🧪 .env Setup

### Backend (`/backend`)

```bash
PORT=3000
MONGO_URI=your_mongo_uri_here

NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

## 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```
## 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```
