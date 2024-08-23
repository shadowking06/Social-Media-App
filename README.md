# 🗣️ Social Media Web Application

**NOTE:** Environment keys have been stripped; please use your own keys in `.env` and set up the proxy in `package.json`.

This project is a social media web application inspired by platforms like Signal, Facebook, and Twitter. It includes features such as posting, commenting, sharing posts, user authentication, notifications, and private messaging.

The application is built with **React.js** for the frontend and **Node.js** for backend package management. **MongoDB** is used for data storage.

## 🌟 Features

- **User Authentication:** Secure login and registration system.
- **Posting & Sharing:** Users can post updates and share others' posts.
- **Commenting:** Comment on posts and interact with other users.
- **Notifications:** Real-time notifications for activities.
- **Private Messaging:** Send and receive private messages.

## 🛠️ Technologies Used

- **Frontend:**
  - **React.js**: For building the user interface.
  - **HTML5**, **CSS3**, **JavaScript**: For web development.
  - **BCrypt**: For password hashing.

- **Backend:**
  - **Node.js**: For managing packages and running the server.
  - **REST API**: For client-server communication.

- **Database:**
  - **MongoDB**: For storing user data and application content.

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



