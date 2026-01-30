<div align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2069/2069755.png" alt="BloodHero Logo" width="100" height="100">

  <h1 style="font-size: 3rem; font-weight: bold; margin-top: 20px;">BLOOD<span style="color: #ef4444;">HERO</span></h1>

  <h3>Your droplets of blood are the ocean of hope for someone in need.</h3>

  <p>
    <a href="https://react.dev/">
      <img src="https://img.shields.io/badge/Built%20With-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
    </a>
    <a href="https://tailwindcss.com/">
      <img src="https://img.shields.io/badge/Styling-TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
    </a>
    <a href="https://firebase.google.com/">
      <img src="https://img.shields.io/badge/Auth-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
    </a>
  </p>

</div>

---

## 📖 About The Project

**BloodHero** is a web application designed to **connect blood donors with patients in need**. Built with a mobile-first approach, it ensures requesting blood or registering as a donor is **accessible, fast, and secure**.

This repository contains the **Frontend client**, built with **React, TailwindCSS, and Firebase** for authentication and data management. The design is **responsive** and **user-friendly**, offering a seamless experience across devices.

---

## 🚀 Live Demo

<div align="center">
  <h3>
    <a href="https://assignment-11-pre.web.app/" target="_blank">👉 Launch BloodHero Application</a>
  </h3>
</div>

---

## ✨ Key Features

### 🎨 User Experience (UX)
- **Glassmorphism UI:** Modern translucent design using `backdrop-blur` for a premium feel.  
- **Adaptive Theme:** Dark/Light mode with preference persistence.  
- **Responsive Navigation:** Capsule navbar for desktop, smooth drawer menu for mobile.

### 🔐 Security & Authentication
- **Firebase Authentication:** Secure Email/Password login and registration.  
- **Private Routes:** Only authenticated users can access sensitive data.  
- **Form Validation:** Real-time validation with feedback and loading indicators.

### 🏥 Content & Information
- **Health Tips & Donation Guide:** Interactive guides with accordion and magazine-style layout.  
- **Legal Pages:** Terms of Service & Privacy Policy with sticky navigation.  

---

## 📸 Screenshots

| **Home / Dark Mode** | **Health Tips / Light Mode** |
|:---:|:---:|
| <img src="https://via.placeholder.com/600x300/1f2937/ffffff?text=Dark+Mode+UI" alt="Dark Mode" width="100%"> | <img src="https://via.placeholder.com/600x300/ffffff/000000?text=Health+Tips+Page" alt="Health Tips" width="100%"> |

| **Mobile Navigation** | **Legal Pages (Sticky Nav)** |
|:---:|:---:|
| <img src="https://via.placeholder.com/600x300/ef4444/ffffff?text=Mobile+Menu" alt="Mobile View" width="100%"> | <img src="https://via.placeholder.com/600x300/e5e7eb/000000?text=Terms+Of+Service" alt="Terms" width="100%"> |

> Replace these placeholders with actual screenshots from your app for best results.

---

## 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Core** | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) |
| **Styling** | ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white) ![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0EF8?style=flat&logo=daisyui&logoColor=white) |
| **Auth / Backend** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black) |
| **Routing** | ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat&logo=react-router&logoColor=white) |
| **Icons / Alerts** | ![React Icons](https://img.shields.io/badge/React_Icons-e91e63?style=flat&logo=react&logoColor=white) ![SweetAlert2](https://img.shields.io/badge/SweetAlert2-8f4300?style=flat&logo=sweetalert2&logoColor=white) |

---

## 💻 Installation & Setup

Follow these steps to run the project locally:

### 1. Clone the Repository
git clone https://github.com/YOUR_USERNAME/blood-hero-client.git
cd blood-hero-client

### 2. Install Dependencies
npm install

### 3. Environment Variables

Create a .env.local file in the root directory with your Firebase config:
```bash
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```
### 4. Start Development Server
npm run dev

Visit http://localhost:5173
 to view your app.

### 📂 Project Structure
```bash
blood-hero-client/
├── public/              # Static assets
├── src/
│   ├── assets/          # Images & icons
│   ├── components/      # Shared components (Navbar, Footer, etc.)
│   ├── layout/          # Main layouts & dashboard
│   ├── pages/           # Page views (Home, Login, HealthTips)
│   ├── provider/        # AuthProvider (Context API)
│   ├── routes/          # Router configuration
│   └── main.jsx         # App entry point
├── .env.local           # Firebase credentials
└── tailwind.config.js   # TailwindCSS config
```
### 🤝 Contributing
Contributions are welcome!

1. Fork the Project
2. Create your feature branch
```bash
git checkout -b feature/AmazingFeature
````
4. Commit your changes
```bash
git commit -m "Add AmazingFeature"
```
5. Push to the branch
```bash
git push origin feature/AmazingFeature
```
4. Open a Pull Request

### 📄 License

Distributed under the MIT License. See LICENSE file for details.

<div align="center"> <p>Made with ❤️ by <strong>Utsho Paul</strong></p> <p> <a href="https://github.com/utshopaul0002">GitHub</a> • <a href="mailto:utshopaul0002@gmail.com">Contact</a> </p> </div> ```

