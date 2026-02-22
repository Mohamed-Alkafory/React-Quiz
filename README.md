# ⚛️ The React Quiz

[![React Version](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB)](https://react.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JSON-Server](https://img.shields.io/badge/backend-json--server-blue)](https://github.com/typicode/json-server)

An advanced, interactive quiz platform designed to challenge your mastery of React. This project demonstrates high-level state management using the `useReducer` pattern, real-time data fetching, and a custom-built timing engine.

---

## 🔥 Why This Quiz?

Most quiz apps are simple. This one is engineered for **precision** and **performance**:

- **⚡ Professional State Persistence**: Leverages React's `useReducer` to manage complex multi-layered states (loading, active, error, finished) with clean, predictable action-based transitions.
- **⏲️ Real-time Synchronization**: A custom-built timer engine that stays perfectly in sync with the quiz progress, automatically finishing the session when the clock hits zero.
- **📊 Dynamic Evaluation**: Intelligent scoring system that calculates results in real-time, providing instant feedback and persisting high scores across attempts.
- **🎨 Premium UI/UX**: A bespoke dark-themed interface built from the ground up with vanilla CSS, featuring glassmorphism elements and smooth transitions.

---

## 🛠️ Built With

| Component                 | Technology            | Role                               |
| :------------------------ | :-------------------- | :--------------------------------- |
| **State Management**      | `useReducer` Hook     | Unified application logic          |
| **Logic Synchronization** | `useEffect` Hook      | API fetching and timer management  |
| **Backend API**           | `json-server`         | Mock RESTful API for question data |
| **Styling**               | Vanilla CSS3          | Custom variables and design system |
| **Deployment**            | GitHub Pages / Vercel | Scalable hosting solutions         |

---

## 🚀 Getting Started

### 1. Set Up the Environment

Clone the repository and install the core dependencies:

```bash
git clone https://github.com/Mohamed-Alkafory/React-Quiz.git
cd React-Quiz
npm install
```

### 2. Launch the Backend Engine

The quiz requires a data stream provided by `json-server`. Start it in your first terminal:

```bash
npm run server
```

> [!NOTE]
> The server initializes on `http://localhost:9000`. Ensure this port is free!

### 3. Start the Frontend

In a secondary terminal, launch the React development server:

```bash
npm start
```

The application will be live at **`http://localhost:3000`**.

---

## 📂 Architecture Overview

- **`src/components/`**: Modularized UI components including the custom `Timer`, `Progess` bar, and `FinishScreen`.
- **`src/data/`**: The `questions.json` source-of-truth containing the React competency assessment.
- **`src/App.js`**: The central brain using a robust reducer pattern to coordinate the entire application lifecycle.

---

## 🌍 Connect With Me

If you enjoyed this project or have suggestions for improvements, feel free to reach out!

**Mohamed Hamed**

- [GitHub](https://github.com/Mohamed-Alkafory)
- [LinkedIn](https://www.linkedin.com/in/mohamed-alkafory)

---

> _"The best way to learn React is to build React"_ – **Let's Code!**
