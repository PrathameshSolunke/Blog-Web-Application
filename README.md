# Blog-Web-Application
A full-featured Blog Web App built with MERN stack (MongoDB, Express, React.js, Node.js) and Tailwind CSS. Features secure JWT auth, CRUD for blogs &amp; comments, responsive UI across devices, and efficient MongoDB data storage for scalability and seamless user experience.

---

## 🚀 Features
- 🔐 User Authentication & Authorization (JWT)  
- ✍️ Full CRUD for Blogs and Comments  
- 📱 Responsive UI with TailwindCSS  
- 💾 MongoDB Database for efficient storage & retrieval  
- ⚡ RESTful APIs with Express & Node.js  
- 🔄 Secure session handling  

---

## 📂 Folder Structure
/client → React frontend with Tailwind CSS
/server → Node.js + Express backend
/models → Mongoose models (User, Blog, Comment)
/routes → API routes for auth, blogs, and comments
/controllers → Business logic

yaml
Copy code

---

## 🛠️ Tech Stack
- **Frontend:** React.js, TailwindCSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Auth:** JWT  

---

## ⚙️ Installation & Setup

### Clone the repository
```bash
git clone https://github.com/<your-username>/<your-blog-repo>.git
cd <your-blog-repo>
Install dependencies
For backend:

bash
Copy code
cd server
npm install
For frontend:

bash
Copy code
cd client
npm install
Run the app
Backend:

bash
Copy code
npm run dev
Frontend:

bash
Copy code
npm run dev


## 📖 Design Decisions & Trade-offs
Used JWT for stateless authentication (lightweight & scalable).

TailwindCSS for fast, responsive UI development.

MongoDB schema supports scalable blog & comment storage.

Modular architecture → easy maintenance & future enhancements.

🌟 Project Highlights
Blogging platform with blog & comment CRUD functionality

JWT-based secure authentication system

Responsive UI with TailwindCSS

Well-structured, modular codebase

Ready for deployment (Vercel/Netlify for frontend, Render/Heroku for backend)

📌 Future Enhancements
Rich text editor for blogs

Image uploads for posts

Like/Dislike functionality

Pagination & search
