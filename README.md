# LexiCraft AI

LexiCraft AI is a lightweight, serverless educational app designed for high school English teachers to easily generate grade-calibrated vocabulary quizzes using AI context clues. 

Built entirely as a single-page frontend application, it connects directly to the **Google Gemini API** right inside the browser. This eliminates the need for expensive backends, databases, or complex server management, making it perfect for free hosting on **GitHub Pages**.

---

## 🚀 Live Demo
Deploy your own instance using GitHub Pages or open the `index.html` file directly in any modern desktop or mobile browser.

---

## ✨ Features

- **🎯 Academic Level Calibration:** Select specific evaluation tiers targeting 9th Grade through Collegiate (12th) level syntactic structures.
- **🧠 Intelligent Context Generation:** Dynamically generates contextual narrative fill-in-the-blank sentences containing implicit semantic hints.
- **🛡️ Built-in Anti-Cheat System:** Features a "Two-Draft" workflow. If a student misses a word on the first attempt, the app reveals a contextual lightbulb hint. Clicking "Regenerate" rotates the question to an entirely new sentence variant to prevent raw guessing or memorization.
- **🔑 Serverless Client Architecture:** No user data or API keys are ever stored on a remote server. Everything executes locally within the browser session.

---

## 🛠️ Installation & Local Setup

Since LexiCraft AI runs purely on the client side, you do not need to install `npm` dependencies, Python packages, or run a local server.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/lexicraft-ai.git](https://github.com/YOUR-USERNAME/lexicraft-ai.git)
   cd lexicraft-ai
