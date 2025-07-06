# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# 🌐 GrowthProAI – Business Dashboard Frontend

This is the **frontend** of the GrowthProAI Full Stack Assignment. Built using **React.js** and **Tailwind CSS**, it provides a responsive and clean UI for business owners to view simulated Google ratings, review counts, and AI-generated SEO headlines.

### 📍 Live Demo

🔗 [https://growthpro-business-dashboard-reviews-puneetharaj-k-rs-projects.vercel.app](https://growthpro-business-dashboard-reviews-puneetharaj-k-rs-projects.vercel.app)

---

## 🚀 Features

- Business input form (name + location)
- Simulated Google rating and reviews
- AI-style SEO headline from backend
- Regenerate headline button
- Spinner during API calls
- React Context for state management
- Tailwind CSS for clean, responsive design

---

## 📦 Tech Stack

- React.js (functional components)
- Tailwind CSS
- React Context API
- Fetch API for backend calls

---

## 🔧 Setup Instructions

```bash
# Clone the frontend repo
git clone https://github.com/Puneetharajkr/growthpro-business-dashboard-reviews-frontend.git
cd growthpro-business-dashboard-reviews-frontend

# Install dependencies
npm install

# Start the frontend
npm run dev
```

> 🔗 Make sure your backend is running at `http://localhost:5000` in local mode.

---

## 📁 Folder Structure

```
src/
├── components/
│   ├── BusinessForm.jsx
│   ├── DisplayCard.jsx
│   └── Spinner.jsx
├── context/
│   └── BusinessContext.jsx
├── App.jsx
├── index.css
└── main.jsx
```

---

## 📄 Assignment Context

This project simulates how local businesses might view SEO and Google Business insights. It was submitted as part of GrowthProAI's Full Stack Internship Assignment.

---

## 📎 Related Repos

- Backend Repo: [growthpro-business-dashboard-reviews-backend](https://github.com/Puneetharajkr/growthpro-business-dashboard-reviews-backend)
- Fullstack Repo: [growthpro-business-dashboard-reviews-fullstack](https://github.com/Puneetharajkr/growthpro-business-dashboard-reviews-fullstack)
