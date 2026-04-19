# 🌐 AI Portfolio Generator

An AI-powered Streamlit application that converts a resume (PDF/DOCX) into a fully functional **portfolio website (HTML, CSS, JS)** using Google's Gemini LLM.

---

## 🚀 Features

* 📄 Upload resume (PDF or DOCX)
* 🤖 AI extracts structured information:

  * Name
  * Summary
  * Skills
  * Experience
  * Projects
  * Education
  * Achievements
* 🎨 Choose design theme:

  * Modern
  * Minimal
  * Dark
  * Creative
* 💻 Auto-generates:

  * `index.html`
  * `style.css`
  * `script.js`
* 🔍 Live website preview
* 📦 Download ready-to-host ZIP file

---

## 🧠 Tech Stack

* **Frontend/UI:** Streamlit
* **LLM:** Google Gemini (via LangChain)
* **Libraries Used:**

  * PyPDF2 (PDF parsing)
  * python-docx (DOCX parsing)
  * LangChain Google GenAI
  * dotenv

---

## 📂 Project Structure

```
├── app.py
├── .env
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/ai-portfolio-generator.git
cd ai-portfolio-generator
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Setup environment variables

Create a `.env` file:

```
GEMINI_API_KEY=your_api_key_here
```

---

## ▶️ Run the App

```
streamlit run app.py
```

---

## 📸 How It Works

1. Upload your resume (PDF/DOCX)
2. Select a website theme
3. Click **Generate Portfolio Website**
4. Preview your website instantly
5. Download ZIP and deploy anywhere (GitHub Pages, Netlify, etc.)

---

## 🧩 Core Workflow

```
Resume → Text Extraction → LLM Structuring → Website Generation → Preview → Download
```

---

## ⚠️ Limitations

* Complex resume formatting may affect extraction accuracy
* Generated design depends on LLM output consistency
* Requires active internet (Gemini API)

---

## 💡 Future Improvements

* Add multiple layout templates
* Drag-and-drop section editing
* Image/profile photo support
* Hosting directly from app
* Multi-language support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make changes
4. Submit a pull request


## 🙌 Acknowledgements

* Google Gemini AI
* LangChain
* Streamlit

---

## 👨‍💻 Author

**Your Name**
GitHub: [https://github.com/Syedzabiulla125](https://github.com/Syedzabiula125)
---

⭐ If you like this project, give it a star!
