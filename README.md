# 📝 Blog Management App

A simple full-stack blog application built with **Node.js**, **Express**, **EJS**, and **Axios**.  
It features two separate servers:  
- **API Server** (`index.js`) — Handles blog post CRUD operations.  
- **Frontend Server** (`server.js`) — Renders the UI and communicates with the API server.

---

## 📌 Features

- View all blog posts  
- View a single blog post by ID  
- Create new blog posts  
- Edit existing blog posts (partial updates supported)  
- Delete blog posts  
- Clean, responsive UI built with **EJS templates**  
- In-memory storage (no database — great for learning purposes)

---

## 📂 Project Structure

Blog_API/
│
├── index.js # API Server (CRUD operations for posts)
├── server.js # Frontend Server (renders pages using EJS)
├── views/
│ ├── index.ejs # Homepage view (list of posts)
│ ├── modify.ejs # Create/Edit post view
├── public/
│ └── styles/ # CSS files
└── package.json

2️⃣ Install dependencies
npm install

3️⃣ Run the API server (port 4000)
node index.js

4️⃣ Run the frontend server (port 3000)
node server.js
