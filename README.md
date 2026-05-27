🧠 AI-Powered LaTeX Code Generator
An intelligent web-based application that converts natural language prompts into LaTeX code using Google Gemini API, with real-time rendering and a modern interactive UI.

🚀 Features
🔹 Convert plain English into valid LaTeX code
🔹 Real-time LaTeX rendering and preview
🔹 Clean and responsive UI with animations
🔹 Powered by Google Gemini API
🔹 Backend built using Flask
🔹 Frontend built using HTML, CSS & JavaScript
🔹 Deployed using Vercel
🔹 Supports equations, integrals, symbols & math expressions

🛠️ Tech Stack
Frontend:
HTML5
CSS3
JavaScript
MathJax (for rendering equations)

Backend:
Python
Flask
Google Gemini API

Deployment:
Vercel
REST API architecture

AI-LaTeX-Generator/
│
├── api/
│   └── index.py           # Flask backend (Gemini API integration)
│
├── frontend/
│   ├── index.html         # UI layout
│   ├── style.css          # Styling
│   ├── script.js          # Client-side logic
│
├── requirements.txt       # Python dependencies
├── vercel.json            # Deployment config
└── README.md

⚙️ How It Works:

* User enters a prompt (e.g., "Integral of x²")
*Request is sent to the Flask backend
*Gemini API generates LaTeX code
*Code is returned and rendered using MathJax
*Output is displayed in real-time

🧪 Example Input
Show the integral of x squared

Output
\int x^2 dx = \frac{x^3}{3} + C

🖥️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-latex-generator.git
cd ai-latex-generator

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Set Gemini API Key
export GEMINI_API_KEY=your_api_key_here

4️⃣ Run the App
python api/index.py


🌐 Deployment:
The project is deployed using Vercel with:
Backend: Python Serverless Functions
Frontend: Static Hosting

📌 Key Highlights

✔ Natural language → LaTeX conversion
✔ Clean UI with animations
✔ Real-time rendering
✔ Cloud-deployed
✔ Beginner-friendly & scalable

**Preview link: latex-code-generator.vercel.app

👨‍💻 Author

Arif Mondal
🎓 B.Tech CSE (AI & ML)
🏫 Institute of Engineering & Management, Kolkata
💡 AI | ML | Cloud | Python
