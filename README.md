# 🗣️ Social Media Web Application

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

**NOTE:** Environment keys have been stripped; please use your own keys in `.env` and set up the proxy in `package.json`.

This project is a social media web application inspired by platforms like Signal, Facebook, and Twitter. It includes features such as posting, commenting, sharing posts, user authentication, notifications, and private messaging.

The application is built with **React.js** for the frontend and **Node.js** for backend package management. **MongoDB** is used for data storage.

## 🌟 Features

- 🔐 **User Authentication:** Secure login and registration system.
- 📝 **Posting & Sharing:** Users can post updates and share others' posts.
- 💬 **Commenting:** Comment on posts and interact with other users.
- 🔔 **Notifications:** Real-time notifications for activities.
- 📩 **Private Messaging:** Send and receive private messages.

## 🛠️ Technologies Used

- **Frontend:**
  - ![React](https://img.shields.io/badge/React.js-16.13.1-blue)
  - **HTML5**, **CSS3**, **JavaScript**: For web development.
  - ![BCrypt](https://img.shields.io/badge/BCrypt-v5.0.1-blueviolet)

- **Backend:**
  - ![Node.js](https://img.shields.io/badge/Node.js-v14.17.0-brightgreen)
  - **REST API**: For client-server communication.

- **Database:**
  - ![MongoDB](https://img.shields.io/badge/MongoDB-v4.4.6-green)

## 🗂️ File Structure

```plaintext
social-media-app/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── server/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│   └── package.json
└── README.md
