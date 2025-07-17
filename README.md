# 📌 PostIt – A Full-Stack Social Media Application

**Developed by:** Uppuluri Hema Sai Ganesh  
**University:** VIT-AP University  
**Tech Stack:** MongoDB, Express, React, Node.js (MERN)  
**Deployed at:** [https://post-it-heroku.herokuapp.com](https://post-it-heroku.herokuapp.com)

---

## ✨ Overview

**PostIt** is a fully-featured social media web application built using the MERN stack. It supports posting, commenting, messaging, and user interaction — designed to be responsive and interactive across devices.

---

## 🚀 Features

- ✅ Create, read, update, and delete posts
- 👍 Like and unlike posts
- 💬 Create, reply to, update, and delete **nested comments**
- 📝 Support for **Markdown** in posts and comments
- 🔐 **JWT Authentication** for Sign up and Login
- 💬 Real-time **private messaging** via socket.io
- 👤 User profiles with posts, liked posts, and comments
- 📜 Infinite scrolling
- 🔍 Search for posts by title
- ⏱ Cooldowns for posting/commenting + **profanity filtering**
- 🧾 View bios and liked-posts of users
- 📊 Sort posts by like count, comment count, and creation date
- ✅ Fully responsive design for all devices

---

## 🛠 Installation & Usage

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/social-media-app.git
cd social-media-app
PostIt
PostIt is a fully-featured social media web application, built with the MERN stack.

Deployed at: https://post-it-heroku.herokuapp.com/
GIF of PostIt walkthrough

Features
Create, read, update and delete posts
Like and unlike posts
Create, reply to, read, update and delete nested comments
Markdown for posts and comments
Sign up and login using JWT for authentication
Private message users in real-time using socket.io
View profiles of users and browse through their posts, liked posts and comments
Infinite scrolling
Sort posts by attributes such as like count, comment count and date created
Profanity filtering and posting/commenting cooldowns
Update bio which can be viewed by other users
Search for posts by their title
View the users who liked a particular post
Fully responsive layout
Installation and usage
Clone this repository
git clone https://github.com/ihtasham42/social-media-app.git
Install dependencies
cd social-media-app  
npm install
cd client
npm install
Create .env in root directory
cd ..
touch .env
Configure environment variables in your new .env file. To acquire your MONGO_URI, create a cluster for free over at https://www.mongodb.com/. The TOKEN_KEY is a secret key of your choosing, you can generate one at this site: https://randomkeygen.com/.
MONGO_URI=<YOUR_MONGO_URI> 
TOKEN_KEY=<YOUR_TOKEN_KEY>
PORT=4000
Run the server
npm run server
Start a new terminal and run react's development server
cd social-media-app
cd client
npm start
Screenshots
Explore view
image

Post view
image

Nested comments
image

Profile view
image

Real-time private messenger
image

Search view
image
