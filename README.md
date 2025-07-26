**💊 PharmaGPT**
PharmaGPT is an AI-powered web application for answering pharmacology-related questions, checking drug interactions, and delivering FAQs using a FastAPI backend and a React + Vite + TypeScript frontend.

---
**🚀 Features**
- Drug FAQ chatbot powered by AI logic
- FastAPI backend for NLP, processing, and routing
- Vite + React frontend with Tailwind CSS
- Real-time interaction between frontend and backend via REST API
---
**🧰 Tech Stack**
- Frontend: React, Vite, TypeScript, Tailwind CSS
- Backend: FastAPI, Uvicorn
- API Communication: REST (JSON)
- Deployment: GitHub
---
**⚙️ Installation & Setup**

 **🔧 Backend (FastAPI)**
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

**🖥️ Frontend (Vite + React)**

```bash
cd pharmagpt/frontend/pharmagpt-ui
npm install

# Start the dev server
npm run dev
```

> The frontend will run at `http://localhost:5173`

---

**🔗 API Routes (FastAPI)**

* `GET /` — Root welcome route
* `POST /chat` — Accepts user input and returns a chatbot response

---
**👤 Author**

GitHub: [@glorythe21st-web](https://github.com/glorythe21st-web)
---
**📝 License**
This project is licensed under the MIT License.
