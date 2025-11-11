# DevRoot - Full Stack MERN Application

## About The Project

**DevRoot** is a developer-focused networking platform inspired by Tinder and DevTinder by Akshay Saini's Namaste Node.js course, allowing developers to connect based on shared interests and projects. This project is built using the **MERN stack** (MongoDB, Express, React, Node.js), with additional libraries for state management, animations, and authentication.

## 🚀 **Technologies Used**

### **Frontend Technologies**

| Technology                                                                                                                    | Description                                       |
| ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)                 | For building the user interface.                  |
| ![Redux](https://img.shields.io/badge/redux-%23764ABC.svg?style=for-the-badge&logo=redux&logoColor=white)                     | For state management across the application.      |
| ![Tailwind CSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) | For utility-first CSS styling.                    |
| ![Axios](https://img.shields.io/badge/axios-%235A29E4.svg?style=for-the-badge)                                                | For making HTTP requests to the backend.          |
| ![Sooner](https://img.shields.io/badge/sooner-%231DA1F2.svg?style=for-the-badge)                                              | For handling asynchronous operations efficiently. |
| ![Framer Motion](https://img.shields.io/badge/framer%20motion-%23FF0080.svg?style=for-the-badge&logo=framer&logoColor=white)  | For adding smooth animations to the UI.           |
| ![React-Icons](https://img.shields.io/badge/react--icons-%2361DAFB.svg?style=for-the-badge)                                   | For adding icons in the UI.                       |
| ![React Markdown Editor Lite](https://img.shields.io/badge/react--markdown--editor--lite-%2320232a.svg?style=for-the-badge)   | For rich text markdown editing.                   |
| ![Dotenv](https://img.shields.io/badge/dotenv-%2300C853.svg?style=for-the-badge)                                              | For managing environment variables.               |

### **Backend Technologies**

| Technology                                                                                                            | Description                                                    |
| --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| ![Node.js](https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node.js&logoColor=white)       | JavaScript runtime environment.                                |
| ![Express.js](https://img.shields.io/badge/express.js-%23000000.svg?style=for-the-badge&logo=express&logoColor=white) | Framework for building RESTful APIs.                           |
| ![Mongoose](https://img.shields.io/badge/mongoose-%238D4F00.svg?style=for-the-badge)                                  | For interacting with MongoDB using object data modeling (ODM). |
| ![JWT](https://img.shields.io/badge/jwt-%23FF5722.svg?style=for-the-badge)                                            | For secure authentication and session management.              |
| ![Bcrypt](https://img.shields.io/badge/bcrypt-%2300C853.svg?style=for-the-badge)                                      | For hashing passwords to enhance security.                     |
| ![CORS](https://img.shields.io/badge/cors-%23007ACC.svg?style=for-the-badge)                                          | For handling cross-origin requests.                            |
| ![Cookie-Parser](https://img.shields.io/badge/cookie--parser-%23FF9800.svg?style=for-the-badge)                       | For parsing cookies in HTTP requests.                          |
| ![Nodemon](https://img.shields.io/badge/nodemon-%237EBC59.svg?style=for-the-badge)                                    | For automatic server restarts during development.              |
| ![Dotenv](https://img.shields.io/badge/dotenv-%2300C853.svg?style=for-the-badge)                                      | For managing environment variables.                            |

### **Database & Tools**

| Technology                                                                                                                    | Description                                       |
| ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| ![MongoDB Atlas](https://img.shields.io/badge/mongodb%20atlas-%2347A248.svg?style=for-the-badge&logo=mongodb&logoColor=white) | Cloud-based NoSQL database for storing user data. |
| ![Postman](https://img.shields.io/badge/postman-%23FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white)               | For API testing and debugging backend routes.     |
| ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)                  | Hosting service for frontend deployment.          |
| ![Render](https://img.shields.io/badge/render-%23008080.svg?style=for-the-badge&logo=render&logoColor=white)                  | Hosting service for backend deployment.           |

---

## 🛠 **Features & Highlights**

### 🔐 **Authentication & Security**

🔑 **JWT-Based Authentication** – Secure login using **JSON Web Tokens (JWT)**  
🔒 **Bcrypt Password Hashing** – Strong encryption for user passwords  
📩 **Secure Password Reset** – **OTP** or token-based password recovery  
🛂 **Role-Based Access Control** – Separate privileges for **Admin**, **Moderator**, and **Users**

### 📊 **Optimized Data Management**

⚡ **35+ Robust APIs** – Well-structured endpoints for **authentication, user profiles, connections, and more**  
🔍 **Advanced Search & Filtering** – Find developers by **skills, location, and interests**  
📌 **Pagination for Performance** – Efficient API responses for large datasets  
🗄️ **Scalable Database Schema** – **Optimized MongoDB queries** with compound indexes

### 🔗 **User Interaction & Matching**

🔥 **Swipe Mechanism** – **"Interested"**, **"Ignore"**, and **"Skip"** profiles, Tinder-style  
💡 **AI-Powered Matching** – Smart recommendations based on **skills, interests, and activity**  
📨 **Real-Time Messaging** – **Direct chat** once a match is made  
🎯 **Personalized Feed** – User feed adapts dynamically based on **connections & interests**

### 🎨 **UI/UX Enhancements**

🌈 **Framer Motion Animations** – Smooth and fluid transitions  
🌙 **Dark Mode Support** – Switch between light and dark themes  
🔔 **Instant Notifications** – Get real-time updates for messages, connections, and activity

### ⚙️ **Performance & Debugging**

📌 **Comprehensive Error Handling** – Centralized middleware to manage API errors  
🔗 **Integration-Ready APIs** – Easily connect with frontend & third-party services  
📜 **Logging & Debugging Middleware** – Tracks API requests & errors  
🚀 **Rate Limiting & Throttling** – Prevents API abuse and excessive requests

### ☁️ **Deployment & Scalability**

📡 **WebSockets for Real-Time Features** – Enables live messaging & notifications  
🖼️ **Cloud Storage for Media** – Handles **profile pictures and uploads** efficiently  
🚀 **CI/CD Deployment Pipeline** – **Automated deployment** using **GitHub Actions**, **Vercel (frontend)**, and **Render (backend)**



## 📦 **Installation & Setup**

### **1. Clone the Repository**

To get started with the project, clone the repository to your local machine.

```bash
git clone https://github.com/onlyVishesh/Namaste-Nodejs.git
```

### **2. Install Dependencies**

Depending on the season and episode folder may vary.

```bash
cd <folder>
npm install
```

### 3. Configure Environment Variables

Create a .env file in the server folder:

##### Frontend `.env` file

```env
VITE_BackendURL = <Backend_URL>
VITE_EMAILJS_SERVICE_ID = <EmailJS_ID>
VITE_EMAILJS_TEMPLATE_ID = <EmailJS_Template_ID>
VITE_EMAILJS_PUBLIC_KEY = <EmailJS_Public_ID>

```

##### Backend `.env` file

```env
PORT=3000
connectionString = <MongoDB_connection_string>
secretJWT = <Write_any_text>
adminEmails = <comma_seperated_emails_for_admin_role>
moderatorEmails = <comma_seperated_emails_for_moderators_role>
FrontendURL = <Frontend_URL>

ALLOWED_FIELDS = "firstName,lastName,username,avatar,about,skills,gender,status,banner,headline,isPremium"

AWS_ACCESS_KEY = <AWS_Access_Key>
AWS_SECRET = <AWS_Secret>
LIVE_WEBSITE_LINK = <Line_Website_Url>

RAZORPAY_KEY_ID = <Razorpay_Key_ID>
RAZORPAY_KEY_SECRET = <Razorpay_Key_Secret>
RAZORPAY_WEBHOOK_SECRET = <Razorpay_Webhook_secret>
CHAT_ENCRYPTION_KEY=<32_bit_number>
```

### 4. Run the Application

```bash
npm run dev
```




---

## 🤝 Contribution

- Contributions are always welcome!
- Feel free to **fork**, create a **pull request**, or open an **issue** if you have ideas for improvements.
- Let's make this better together! 🚀🔥

## ⭐ Show your support

Give a ⭐️ if this project helped you and try to contribute and share with your developers.
