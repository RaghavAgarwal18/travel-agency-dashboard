# 🌍 Travel Agency Dashboard

A modern full-stack web application for managing trips, customers, itineraries, and AI-powered trip planning. This project simulates the digital platform a travel agency would use to handle bookings and provide curated experiences to clients.  

Designed as a portfolio project, it showcases both **front-end development** (interactive dashboards, data-driven UI) and **back-end integration** (Appwrite database, authentication, APIs, AI with Gemini).

---

## ✨ Features

- 🧑‍💼 **Admin Dashboard** – view stats, manage users, and monitor trip data  
- 🗺️ **Handpicked Trips** – curated travel destinations with images and details  
- 🤖 **AI-Powered Recommendations** – integrates **Google Gemini API** to generate smart travel itineraries  
- 🔑 **Authentication** – secure login/signup via Appwrite  
- 📊 **Dynamic Data** – trips, users, and itineraries stored in Appwrite Database  
- 🎨 **Responsive UI** – styled with Tailwind CSS, optimized for all devices  
- ⚡ **Modern Stack** – React Router v7 with loaders/actions, Syncfusion UI components, Vite dev environment  
- 🔒 **Environment Variables** – secrets managed via `.env` (Appwrite, Syncfusion, Gemini keys)  

---

## 🛠️ Tech Stack

- **React Router v7** – routing, loaders, and SSR-style data handling  
- **Vite** – fast build & dev server  
- **TypeScript** – type-safety and maintainability  
- **Tailwind CSS** – utility-first styling  
- **Syncfusion** – rich UI widgets (grids, charts)  
- **Appwrite** – authentication, database, and storage  
- **Docker** – optional containerized deployment  

---


## 🚀 Getting Started

### 1. Clone & Install
```bash
git clone https://github.com/your-username/travel-agency-dashboard.git
cd travel-agency-dashboard
npm install

```

## 2. Environment Variables
create a .env in your project root
```env
VITE_APPWRITE_API_ENDPOINT=your_appwrite_endpoint
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_db_id
VITE_APPWRITE_USERS_COLLECTION_ID=your_users_collection_id
VITE_APPWRITE_TRIPS_COLLECTION_ID=your_trips_collection_id
VITE_SYNCFUSION_LICENSE_KEY=your_syncfusion_key
GEMINI_API_KEY=your_gemini_key
UNSPLASH_ACCESS_KEY=your_unsplash_key
```

## 3. Run in Development
```bash
npm run dev
```

### Inspiration
This project was inspired by JavaScript Mastery’s tutorial, adapted into a full travel agency dashboard.
