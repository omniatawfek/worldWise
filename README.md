# 🌍 WorldWise Application

WorldWise is a React-based web application that allows users to explore cities and countries they have visited, visualize them on an interactive map, and manage their travel experiences in an organized way.

The project focuses on building a real-world Single Page Application (SPA) while applying modern React concepts and performance optimization techniques.

---

## live Demo

https://world-wise-sepia.vercel.app/

---

## 📌 Project Overview

The WorldWise application enables users to:

- Log in and log out securely
- View visited cities and countries
- Display locations on an interactive map
- Navigate smoothly between different pages
- Experience fast performance with optimized rendering and bundle size

This project was built as a complete learning experience covering advanced React patterns and real-world performance concerns.

---

## 🛠️ Technologies & Tools Used

### Frontend

- **React**
- **React Router**
- **Context API**
- **Hooks**
  - `useState`
  - `useEffect`
  - `useContext`
  - `useCallback`
  - `useMemo`
- **React.lazy & Suspense** (Code Splitting & Lazy Loading)

### Performance Optimization

- Preventing wasted re-renders
- Memoization using `useCallback`
- React Profiler for performance analysis
- Bundle size optimization with code splitting

### Tooling

- **Vite** (Build tool & bundler)
- **ESLint** (Code quality & best practices)
- **Fake API Server** (for development data)
- **React DevTools**

---

## ⚡ Performance Optimizations Applied

- Analyzed component renders using **React Profiler**
- Fixed infinite render loops caused by unstable dependencies
- Used `useCallback` to stabilize functions passed to dependency arrays
- Implemented **Lazy Loading** at the route level
- Reduced initial bundle size by splitting code into multiple chunks

---

## 🧠 Key Concepts Demonstrated

- Single Page Application (SPA) architecture
- Client-side routing
- Global state management with Context API
- Dependency arrays and their impact on rendering
- Lazy loading and Suspense
- Real-world debugging using ESLint warnings
- Understanding and fixing performance bottlenecks

---

## 📂 Project Structure (Simplified)

```text
src/
├── components/
├── contexts/
├── pages/
├── services/
├── hooks/
├── App.jsx
├── main.jsx

🚀 How to Run the Project Locally
Clone the repository:

bash
git clone https://github.com/your-username/worldwise.git

Install dependencies:

bash
npm install

Start the fake API server:

bash
npm run server

Run the development server:

bash
npm run dev

🎯 Learning Outcome
This project was a comprehensive hands-on experience that strengthened understanding of:

Advanced React hooks

Performance optimization strategies

Real-world debugging techniques

Scalable application structure

Production-ready React applications

👩‍💻 Author
Omnia Tawfek

Feel free to explore the project, review the code, and provide feedback.

```
