🌍 WorldWise
📌 Project Overview

WorldWise is a React-based web application that allows users to track cities they have visited around the world.
The app provides an interactive map experience, enabling users to add cities, view details, and organize visited locations by countries.

The project focuses on building a real-world React application using modern React features, clean architecture, and performance optimizations.

🎯 Key Features

🗺️ Interactive map to select and view cities

📍 Add cities with details (name, country, date, notes)

🌐 View visited cities grouped by country

🔐 Authentication-protected routes

⚡ Optimized performance with lazy loading

🔄 Global state management using Context API

🧭 Client-side routing with React Router

🛠️ Technologies & Tools Used
⚛️ Frontend

React

Hooks (useState, useEffect, useContext, useReducer)

Custom Hooks

React.memo

Suspense & lazy for code splitting

React Router

Nested Routes

Protected Routes

URL-based navigation

🧠 State Management

Context API

CitiesContext for global state

Custom hook (useCities) to consume context safely

Centralized logic for fetching and managing data

🚀 Performance Optimization

Code Splitting

Lazy loading pages using React.lazy

Loading fallback using Suspense

Optimized Renders

Avoiding prop drilling

Memoization where needed

🧰 Tooling

Vite – fast development & optimized production builds

ESLint – code quality and consistency

CSS Modules – scoped and maintainable styles

📂 Project Structure (Simplified)
src/
│
├── components/ # Reusable UI components
├── pages/ # App pages (lazy loaded)
├── contexts/ # Context API providers
├── hooks/ # Custom hooks
├── services/ # API & data logic
├── App.jsx
└── main.jsx

⚙️ Key Concepts Applied

Single Page Application (SPA)

Client-side routing

Global state via Context API

Custom hooks for cleaner code

Lazy loading & bundle optimization

Separation of concerns

Scalable project structure

🚀 Getting Started
Install dependencies
npm install

Run development server
npm run dev

Build for production
npm run build

📈 Learning Outcomes

This project demonstrates:

How to structure a medium-scale React application

How to manage global state without external libraries

How to optimize bundle size and app performance

How to write clean, maintainable, and scalable React code

🏁 Final Notes

WorldWise was built as a hands-on learning project to apply modern React concepts in a practical scenario.
It reflects real-world patterns commonly used in professional React applications.

You can check out the live version of the project here:
https://9wvspztv-5173.uks1.devtunnels.ms/
