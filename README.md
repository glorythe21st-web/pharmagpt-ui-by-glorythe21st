```markdown
💊 PharmaGPT

**PharmaGPT** is an AI-powered web application for answering pharmacology-related questions, checking drug interactions, and delivering FAQs using a FastAPI backend and a React + Vite + TypeScript frontend.

---

 📁 Project Structure

```

pharmagpt/
├── backend/          # FastAPI backend (API, logic, and data)
├── frontend/
│   └── pharmagpt-ui/ # Vite + React + TypeScript frontend

````

---

🚀 Features

- Drug FAQ chatbot powered by AI logic
- FastAPI backend for NLP, processing, and routing
- Vite + React frontend with Tailwind CSS
- Real-time interaction between frontend and backend via REST API

---

🧰 Tech Stack

- **Frontend**: React, Vite, TypeScript, Tailwind CSS
- **Backend**: FastAPI, Uvicorn
- **API Communication**: REST (JSON)
- **Deployment**: GitHub

---

⚙️ Installation & Setup

 🔧 Backend (FastAPI)

```bash
cd pharmagpt/backend
python -m venv venv
venv\Scripts\activate     # On Windows
pip install -r requirements.txt

 Run the server
uvicorn main:app --reload
````

> The backend will run at `http://127.0.0.1:8000`

---

### 🖥️ Frontend (Vite + React)

```bash
cd pharmagpt/frontend/pharmagpt-ui
npm install

# Start the dev server
npm run dev
```

> The frontend will run at `http://localhost:5173`

---

## 🔗 API Routes (FastAPI)

* `GET /` — Root welcome route
* `POST /chat` — Accepts user input and returns a chatbot response

---

## 📦 Build Frontend for Production

```bash
npm run build
```

---

## 📤 Deployment

You can deploy to platforms like:

* **Backend**: Render, Railway, or Deta
* **Frontend**: Vercel, Netlify, or GitHub Pages (via static export)

---

## 🧠 Future Improvements

* Add authentication and user history
* Integrate drug interaction APIs (e.g., RxNav)
* Add logging and analytics to the chatbot
* Add search, filter, and mobile support

---

## 👤 Author

* GitHub: [@glorythe21st-web](https://github.com/glorythe21st-web)

---

## 📝 License

This project is licensed under the MIT License.

````
