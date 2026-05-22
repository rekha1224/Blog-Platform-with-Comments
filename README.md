# Blog Platform with Comments

A full-stack Blogging Platform that allows users to create, edit, and manage blog posts while enabling readers to interact through comments. The application includes secure authentication, RESTful APIs, database integration, and responsive design for seamless user experience.

## Features

### User Features

* User Registration & Login
* Secure Authentication using JWT
* Create Blog Posts
* Edit Existing Posts
* Delete Blog Posts
* View All Blogs
* Read Individual Blog Posts
* Add Comments on Posts
* Responsive Design for Mobile and Desktop

### Admin Features (Optional)

* Manage Users
* Delete Inappropriate Posts
* Moderate Comments

---

# Tech Stack

## Frontend

* React.js
* HTML5
* CSS3
* JavaScript
* Axios

## Backend

* Node.js
* Express.js

## Database

Choose any one:

* MongoDB
* MySQL
* PostgreSQL

## Authentication

* JWT (JSON Web Token)
* bcrypt.js

---

# Project Structure

```bash id="a7q2p1"
blog-platform/
│
├── client/                     # Frontend React Application
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/                     # Backend Node.js Application
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── screenshots/
├── README.md
└── package.json
```

---

# Installation

## Clone Repository

```bash id="2j9q7d"
git clone https://github.com/your-username/blog-platform.git
cd blog-platform
```

---

# Backend Setup

## Navigate to Server Folder

```bash id="9q0mde"
cd server
```

## Install Dependencies

```bash id="l2x7s1"
npm install
```

## Create `.env` File

```env id="9f8m2v"
PORT=5000
MONGO_URI=your_database_connection
JWT_SECRET=your_secret_key
```

For MySQL/PostgreSQL:

```env id="v4s8qe"
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=blog_platform
```

---

## Start Backend Server

```bash id="r8t5n1"
npm start
```

Backend runs on:

```bash id="u1d7y3"
http://localhost:5000
```

---

# Frontend Setup

## Navigate to Client Folder

```bash id="n6m8x0"
cd client
```

## Install Dependencies

```bash id="z4k1q7"
npm install
```

## Start Frontend

```bash id="f2d9p6"
npm start
```

Frontend runs on:

```bash id="g7s3m2"
http://localhost:3000
```

---

# API Endpoints

## Authentication Routes

| Method | Endpoint             | Description   |
| ------ | -------------------- | ------------- |
| POST   | `/api/auth/register` | Register User |
| POST   | `/api/auth/login`    | Login User    |

---

## Blog Routes

| Method | Endpoint         | Description          |
| ------ | ---------------- | -------------------- |
| GET    | `/api/posts`     | Get All Blog Posts   |
| GET    | `/api/posts/:id` | Get Single Blog Post |
| POST   | `/api/posts`     | Create Blog Post     |
| PUT    | `/api/posts/:id` | Update Blog Post     |
| DELETE | `/api/posts/:id` | Delete Blog Post     |

---

## Comment Routes

| Method | Endpoint                | Description           |
| ------ | ----------------------- | --------------------- |
| GET    | `/api/comments/:postId` | Get Comments for Post |
| POST   | `/api/comments/:postId` | Add Comment           |
| DELETE | `/api/comments/:id`     | Delete Comment        |

---

# Screenshots

Add project screenshots here.

Example:

```md id="q7m2v8"
![Home Page](screenshots/home.png)
![Blog Page](screenshots/blog.png)
![Create Post](screenshots/create-post.png)
![Comments Section](screenshots/comments.png)
```

---

# Future Enhancements

* Rich Text Editor
* Like and Share Features
* Categories and Tags
* Search Functionality
* User Profile Pages
* Dark Mode
* Email Notifications
* Bookmark Posts

---

# Learning Outcomes

By building this project, you will learn:

* Full-stack web development
* RESTful API creation
* Authentication and authorization
* CRUD operations
* Database integration
* Content management systems
* User interaction handling
* Frontend and backend integration
* Responsive web design

---

# Author

Developed by Rekha Kamthar

---

# License

This project is licensed under the MIT License.
