# 🧠 AI-Powered LaTeX Code Generator

An intelligent, web-based application that converts natural language prompts into valid LaTeX code using the Google Gemini API. It features real-time rendering and a modern, interactive user interface designed for students, researchers, and developers.

🔗 **[Live Demo](https://latex-code-generator.vercel.app)**

---

## 🚀 Features

* **Natural Language Processing:** Convert plain English prompts into highly accurate LaTeX expressions.
* **Real-Time Rendering:** Instantly preview rendered equations as you type or generate them, powered by MathJax.
* **Modern Interactive UI:** A clean, responsive design featuring smooth CSS animations and intuitive layouts.
* **Robust Backend:** Built with a lightweight Python Flask architecture integrated with the Google Gemini API.
* **Serverless Deployment:** Fully optimized for seamless, cost-effective hosting on Vercel.
* **Comprehensive Math Support:** Handles equations, integrals, matrices, Greek symbols, and complex math formulas.

---

## 🛠️ Tech Stack

### Frontend
* **HTML5 & CSS3:** For semantic structure and elegant responsive styling.
* **JavaScript (ES6+):** Manages asynchronous API calls and interactive UI states.
* **MathJax:** Client-side JavaScript engine for crisp rendering of LaTeX math strings.

### Backend
* **Python:** Main application language.
* **Flask:** Lightweight WSGI web application framework.
* **Google Gemini API:** LLM integration for interpreting natural language and generating syntax-accurate LaTeX.

### Deployment & Architecture
* **Vercel:** Hosted as a combination of Static Frontend assets and Python Serverless Functions.
* **REST API:** Clean separation of concerns between client requests and AI generation endpoints.

---

## 📁 Project Structure

```text
AI-LaTeX-Generator/
│
├── api/
│   └── index.py          # Flask backend (Gemini API integration & Serverless entrypoint)
│
├── frontend/
│   ├── index.html        # Main UI layout
│   ├── style.css         # Custom animations and application layout
│   └── script.js         # API communication and MathJax orchestration
│
├── requirements.txt      # Python dependencies
├── vercel.json           # Vercel serverless deployment configuration
└── README.md             # Project documentation
