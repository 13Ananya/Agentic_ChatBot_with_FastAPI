Here's a professional `README.md` file for your AI Agentic Chatbot project:  

---

# 🚀 Personal Agentic AI Chatbot  

An advanced AI chatbot powered by **LangGraph, FastAPI, Streamlit, and OpenAI**, designed to interact intelligently using **ReAct Agents** and external search tools.  

## 🔥 Features  

- **Conversational AI:** Utilizes **LLMs** (Groq, OpenAI, Meta Llama, Mistral) for human-like responses.  
- **Agentic Capabilities:** Implements **search tools** for real-time information retrieval.  
- **Modular Backend:** Built using **FastAPI** with proper **Pydantic schema validation**.  
- **Interactive UI:** Developed with **Streamlit**, allowing users to customize model selection, system prompts, and queries.  
- **Production Ready:** Easily deployable with **Uvicorn** for hosting.  

## 📌 Project Layout  

### **Phase 1 – Create AI Agent**  
- Configure API keys for **Groq** and **Tavily**.  
- Set up **LLM & AI tools**.  
- Implement **AI Agent** with search functionality.  

### **Phase 2 – Setup Backend (FastAPI)**  
- Define **Pydantic models** for schema validation.  
- Handle AI agent requests from the frontend.  
- Run the app & explore **Swagger UI Docs**.  

### **Phase 3 – Setup Frontend**  
- Build an interactive UI with **Streamlit**.  
- Integrate **frontend with backend** using API endpoints.  

## 🛠️ Tech Stack  

| Component      | Technology Used |
|---------------|----------------|
| **Backend**   | FastAPI, Python, Uvicorn |
| **Frontend**  | Streamlit |
| **AI Models** | OpenAI, Groq, Meta Llama, Mistral |
| **Agents**    | LangGraph, LangChain |
| **Hosting**   | Uvicorn |
| **Development** | VS Code |

## ⚡ Getting Started  

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/13Ananya/Agentic_ChatBot_with_FastAPI.git  
cd Agentic_ChatBot_with_FastAPI
```

### 2️⃣ **Create a Virtual Environment**  
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### 3️⃣ **Install Dependencies**  
```bash
pip install -r requirement.txt  
```

### 4️⃣ **Set API Keys (Groq & Tavily)**  
Create a `.env` file and add:  
```ini
GROQ_API_KEY=your_key_here
TAVILY_API_KEY=your_key_here
```

### 5️⃣ **Run the Backend Server**  
```bash
python backend.py
```
_Check if FastAPI is running at_ `http://127.0.0.1:9999`  

### 6️⃣ **Run the Frontend (Streamlit UI)**  
```bash
streamlit run frontend.py
```
_Access UI at_ `http://localhost:8501`  

## 📜 API Endpoints  

| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/chat` | Sends a query to the AI chatbot |
| `GET`  | `/docs` | Opens FastAPI Swagger UI |

## 📌 Contributing  

1. Fork the repository  
2. Create a new branch: `git checkout -b feature-name`  
3. Commit your changes: `git commit -m "Added new feature"`  
4. Push to your branch: `git push origin feature-name`  
5. Open a pull request  

## 🏆 Acknowledgments  

- **LangGraph** for AI agent orchestration  
- **FastAPI** for robust backend services  
- **Streamlit** for interactive UI  
- **Groq, OpenAI, and Meta Llama** for LLMs  

---

**🚀 Let's build intelligent AI agents together!**
