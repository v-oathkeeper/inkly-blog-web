# 📝 Inkly – Fullstack AI Blogging Platform

Inkly is a modern, fullstack blogging web application built with the MERN stack and powered by Gemini AI. Users can write, publish, and manage blogs with media support, while admins can control publication status and manage content with ease.

---

## 🚀 Features

- 🔐 **Admin Authentication**
- 🖼️ **Image Uploads via ImageKit**
- ✍️ **Create, Edit, Delete Blog Posts**
- 📚 **Blog Categories & Filtering**
- 💬 **Blog Comments System**
- 🧠 **Gemini AI Integration** – auto-generate blog content
- 🧾 **Admin Dashboard** – manage blogs, publish/unpublish, delete
- ⚡ Fully responsive, clean UI built with **React** and **Tailwind CSS**

---

## 📸 Demo Credentials

```
Login:    admin@example.com  
Password: oathkeeper
```

---

## 🧱 Tech Stack

- **Frontend:** React, Vite, TailwindCSS
- **Backend:** Node.js, Express
- **Database:** MongoDB (via Atlas)
- **AI Integration:** Gemini API
- **Media Uploads:** ImageKit
- **State Management:** React Context API
- **Authentication:** Token-based (via middleware)

---

## 🛠️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/inkly-blog-app.git
cd inkly-blog-app
```

### 2. Install dependencies

```bash
# Frontend
cd client
npm install

# Backend
cd server
npm install
```

### 3. Environment Variables

Create a `.env` file in `server/` with:

```
MONGO_URI=your_mongodb_atlas_uri
GEMINI_API_KEY=your_gemini_api_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
JWT_SECRET=your_jwt_secret
```

> Make sure `.env` is added to `.gitignore`

---

## 🧪 Running the App

### Frontend (Vite)

```bash
cd client
npm run dev
```

### Backend (Express)

```bash
cd server
npm run server
```

Frontend: http://localhost:5173  
Backend API: http://localhost:3000

---

## 📁 Folder Structure

```
Project_2/
├── client/         # Frontend (React)
├── server/         # Backend (Express)
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── middleware/
└── README.md
```

---

## 📌 API Highlights

- `POST /api/auth/login` – Admin login
- `POST /api/blog/add` – Add blog with image upload
- `GET /api/blog/all` – Get all published blogs
- `POST /api/blog/toggle-publish` – Toggle blog publish status
- `POST /api/blog/delete` – Delete a blog
- `POST /api/blog/update` – Update a blog post
- `POST /api/blog/add-comment` – Add comment
- `POST /api/blog/comments` – Fetch comments
- `POST /api/gemini/generate` – Generate content using Gemini AI

---

## 🧠 AI Blog Content Generator

Powered by **Google Gemini API** — just enter a topic, and Inkly will auto-generate a blog draft to get you started.

---

## 👨‍💻 Author

Built by [Your Name]  
For internship project: `Oathkeeper/Project_2`

---

## 🛡️ License

MIT License

---

## 🙌 Feedback / Support

Feel free to raise issues or contribute improvements!
