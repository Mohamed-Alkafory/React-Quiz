# ⚛️ The React Quiz

![React Quiz Banner](react_quiz_banner.png)

A polished, interactive quiz application built with **React** to test your knowledge of the React ecosystem. This project features a custom-built hook-based state management system, a sleek dark-themed UI, and a real-time countdown timer.

---

## 🚀 Features

- **Dynamic Question Loading**: Questions are fetched from a mock API using `json-server`.
- **Interactive UI**: Real-time feedback on correct and incorrect answers.
- **Score Tracking**: Automatic point calculation based on question difficulty.
- **Progressive Flow**: Tracks your progress through the quiz with a visual progress bar.
- **Countdown Timer**: Stakes are high! Complete each question before time runs out.
- **High Score Persistence**: Challenges you to beat your previous best.
- **Responsive Layout**: Optimized for various screen sizes with clean CSS.

---

## 🛠️ Tech Stack

- **Frontend**: [React](https://react.dev/) (Hooks, `useReducer`)
- **Styling**: Vanilla CSS (Custom properties, Flexbox/Grid)
- **Backend (Mock)**: [JSON Server](https://github.com/typicode/json-server) for data persistence.
- **Fonts**: [Codystar](https://fonts.google.com/specimen/Codystar) via Google Fonts.

---

## 🚦 Getting Started

Follow these steps to get the quiz up and running locally.

### 1. Clone the project

```bash
git clone https://github.com/Mohamed-Alkafory/react-quiz.git
cd react-quiz
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the Backend (JSON Server)

The app relies on a mock API. Start the server first in a separate terminal:

```bash
npm run server
```

_The server will run on [http://localhost:9000](http://localhost:9000)_

### 4. Start the Application

In another terminal, run:

```bash
npm start
```

_The app will launch on [http://localhost:3000](http://localhost:3000)_

---

## 📁 Project Structure

```text
src/
├── components/          # Reusable UI components
│   ├── App.js           # Main application logic (useReducer)
│   ├── Header.js        # App header component
│   ├── Question.js      # Individual question rendering
│   ├── Progress.js      # Quiz progress indicator
│   ├── Timer.js         # Countdown timer logic
│   └── ...
├── data/
│   └── questions.json   # Mock database for quiz questions
├── index.css            # Global styles and design system
└── index.js             # Application entry point
```

---

## 🔮 Future Roadmap

- [ ] Support for multiple quiz categories.
- [ ] Adaptive difficulty levels.
- [ ] Integration with a real backend database.
- [ ] User authentication and globally stored high scores.

---

## 📝 License

This project is licensed under the MIT License. Feel free to use and modify it!

---

_Made with ❤️ by [Mohamed Hamed](https://github.com/Mohamed-Alkafory)_
