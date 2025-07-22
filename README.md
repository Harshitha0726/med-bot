# 🩺 MedBot – AI Health Assistant

A lightweight, **responsive** medical chatbot powered by **Google Gemini-2.0**.  
Ask about symptoms or illnesses and receive concise, evidence-based guidance.

---

## 📸 Screenshot
![Demo](static/img/screenshot.png)

---

## 🚀 Live Demo
https://medbot-xyz.onrender.com

---

## 🔧 Local Development (Windows)

 **Clone**
   ```bash
   git clone https://github.com/Harshitha0726/med-bot.git
   cd med-bot
   ```
## Virtual Environment
```bash
   py -m venv venv
  venv\Scripts\activate
  pip install -r requirements.txt
```
## Secrets
  Create .env in project root:
  GOOGLE_API_KEY=YOUR_GEMINI_KEY

## Run
```bash
  python app.py
```

## Project Tree
```bash
medbot/
├── app.py                 # Flask back-end
├── requirements.txt
├── Procfile               # Render / Railway
├── .env                   # secrets (git-ignored)
├── templates/
│   └── index.html
├── static/
│   ├── css/
   │   └── style.css
│   ├── js/
   │   └── chat.js
│   └── img/
│       ├── bg.jpg         # background
│       ├── logo.png       # logo
│       └── screenshot.png # demo
└── README.md
```

## 🔐 Disclaimer

  MedBot is not a substitute for professional medical advice.
  Always consult a licensed physician before taking action.
## 🤝 Contributing
  Pull requests welcome!
  Open an issue for bugs or feature requests.
## 📄 License
  MIT © 2025 Harshitha
 ```bash
  Save → `git add README.md && git commit -m "docs: add README" && git push`
 ```
