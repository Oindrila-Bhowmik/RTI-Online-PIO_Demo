# 🧾 RTI-Online-PIO_Demo

🔗 **Live Demo:** [https://rti-online-pio-demo.vercel.app](https://rti-online-pio-demo.vercel.app)

---

## 📌 Project Overview
This project is a demo frontend for an RTI (Right to Information) Online Portal, showcasing the login and dashboard routing logic using modern frontend tools and deployment workflows. Built with React and Vite, it ensures fast loading, clean navigation, and responsive design for a smooth user experience.

---

## 🛠️ Tech Stack Used
- **Frontend Framework:** React.js
- **Bundler & Dev Server:** Vite
- **Routing:** React Router DOM
- **Code Editor:** Visual Studio Code (VS Code)
- **Version Control:** Git & GitHub
- **Deployment:** Vercel

---

## 📄 Project Structure & Pages

### 1. Login Page (`LoginPage.jsx`)
- Entry point of the application (`/`)
- Contains form fields for user credentials
- Routes to the dashboard page on login

### 2. Dashboard Page (`DashboardPage.jsx`)
- Protected route (`/dashboard`)
- Displays mock dashboard content
- Accessible after logging in (simulated for demo)

### 3. App Configuration (`App.jsx`)
- Uses `BrowserRouter`, `Routes`, and `Route`
- Handles all app routing logic

---

## 📱 Responsiveness
- Mobile-first layout
- Smooth responsiveness across desktop, tablet, and mobile
- Lightweight UI components for faster rendering

---

## 🚀 Deployment
- Deployed via [Vercel](https://vercel.com) with GitHub integration
- Auto-deployment on push to `main` branch
- **Production URL:** [https://rti-online-pio-demo.vercel.app](https://rti-online-pio-demo.vercel.app)

---

## ✅ User Efficiency
- Instant page loads due to Vite bundling
- Seamless navigation with React Router
- Clean and simple UI
- Easy to expand with authentication or backend APIs later

---





# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
