# BlogSpace

A full-stack blog application where users can register, log in and manage their own blog posts.

**Live Website:** https://subtle-malabi-a54179.netlify.app
**Backend Repository:** https://github.com/aynaimran29-hub/My-blog-App-backend-tasks

## Features

- User registration and login with JWT authentication
- Protected dashboard (redirects to login without a valid token)
- Each user sees only their own blogs (enforced on the server)
- Create, edit, delete and download blogs
- Search and sort blogs on the dashboard
- Blog detail page
- User profile page and logout
- Responsive design that works on mobile

## Tech Stack

- Frontend: HTML, CSS, JavaScript (hosted on Netlify)
- Backend: Node.js, Express (hosted on Vercel)
- Database: MongoDB Atlas (Mongoose)
- Auth: JSON Web Tokens, bcryptjs

## How to Run Locally

1. Clone the backend repository and run `npm install`.
2. Create a `.env` file with `MONGO_URI`, `JWT_SECRET` and `PORT`.
3. Start the server with `npm start`.
4. In `config.js` set `API_URL` to `http://localhost:5000`.
5. Open the frontend with Live Server and start from `register.html`.

## Pages

register, login, dashboard, create-blog, profile, index (home), blog-detail