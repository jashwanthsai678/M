# 🩺 MedMind AI

> **An AI-powered healthcare assistant built with Gemini API, FastAPI, and Next.js.**

MedMind AI is an intelligent healthcare assistant designed to provide conversational medical guidance, general health information, and curated health news through a modern full-stack web application.

> **⚠️ Project Status:** Active Development 🚧

---

## ✨ Features

* 🤖 AI-powered healthcare conversations using **Google Gemini**
* 💬 Natural language medical Q&A
* 📰 Live Health News section
* ⚡ Fast and responsive Next.js frontend
* 🚀 FastAPI backend with REST APIs
* 📱 Responsive UI for desktop and mobile
* 🔒 Secure environment variable configuration
* ☁️ Cloud deployment

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS

### Backend

* FastAPI
* Python
* Uvicorn

### AI

* Google Gemini API

### Deployment

* **Frontend:** Vercel
* **Backend:** Render

---

## 📂 Project Structure

```
MedMind-AI/
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── public/
│   └── ...
│
├── backend/
│   ├── routes/
│   ├── services/
│   ├── models/
│   ├── main.py
│   └── ...
│
└── README.md
```

---

## 🚀 Live Demo


->  [link](https://m-eosin-five.vercel.app/)


---

## 📸 Screenshots



### Home Page

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/73233381-b96c-4213-8ad7-0daeabc1bcb1" />


### AI Chat

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/d1891ff9-17ce-4383-ab10-a76734598f2a" />


### Finding Specialist Doctor

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/9b28bcc1-2ad9-418c-bbb2-32d6adeb5de9" />



---

## ⚙️ Local Setup

### Clone Repository

```bash
git clone https://github.com/yourusername/MedMind-AI.git

cd MedMind-AI
```

---

### Backend

```bash
cd backend

python -m venv venv

source venv/bin/activate
```

Windows

```powershell
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env`

```env
GEMINI_API_KEY=YOUR_API_KEY
```

Run server

```bash
uvicorn main:app --reload
```

---

### Frontend

```bash
cd frontend

npm install

npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file inside the backend directory.

```env
GEMINI_API_KEY=YOUR_API_KEY
```

---

## ⚠️ API Key Notice

For security reasons, the **Google Gemini API key has been removed from this public repository**.

If you clone this project, you must generate your own Gemini API key and add it to your local `.env` file before running the application.

The deployed application may also be temporarily unavailable whenever the API key has been intentionally removed due to security, quota management, or repository maintenance.

---

## 🗺️ Roadmap

* [x] AI Chat Assistant
* [x] Gemini API Integration
* [x] FastAPI Backend
* [x] Next.js Frontend
* [x] Responsive UI
* [x] Deployment on Render
* [x] Deployment on Vercel
* [ ] Conversation Memory
* [ ] Authentication
* [ ] Medical Report Analysis
* [ ] Voice Assistant
* [ ] Image-based Disease Detection
* [ ] Medicine Recommendation Support
* [ ] Chat History
* [ ] Multi-language Support
* [ ] Streaming AI Responses
* [ ] Docker Support

---

## 🤝 Contributing

Contributions, suggestions, and feature requests are always welcome.

Feel free to fork the repository, open issues, or submit pull requests.

---



## 👨‍💻 Author

**Rahul Pagadimuntala**

GitHub: https://github.com/rahul-505

LinkedIn: https://www.linkedin.com/in/rahul-pagadimuntala-79ba1a23a/

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates continued development.
