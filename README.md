# 🧠 IA Assistant Investigation

**IA Assistant Investigation** is an intelligent research tool built with **Python**, designed to perform **autonomous searches**, analyze results, and generate useful summaries — all directly from the **terminal**.  
It leverages **LangChain** and cloud-based LLMs to combine reasoning, data retrieval, and contextual generation.

> “It doesn’t just search for you — it thinks with you.”

---

## ⚙️ Main Features

- 🔍 Automated web research and information gathering.  
- 🧩 Integration with **LangChain** and **LLM APIs** (GPT / Cloud).  
- 💬 Full **CLI-based** interaction.  
- 📂 Context management and session-based results.  
- 🔐 Secure API key handling via `.env`.  
- 🧠 Foundation for future **multi-agent intelligence**.

---

## 🧰 Tech Stack

| Category | Tools |
|-----------|-------|
| Language | Python 3.x |
| AI Framework | LangChain |
| External APIs | OpenAI / Google Search / others |
| Interface | CLI (Terminal) |
| Containerization | Docker (optional) |
| Configuration | python-dotenv |

---

## 🚀 Installation

### 1️⃣ Clone the repository

git clone https://github.com/Matrinoza/Ia-asistant-investigation.git
cd Ia-asistant-investigation


### 2️⃣ Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # Linux
venv\Scripts\activate     # Windows

### 3️⃣ Install dependencies
pip install -r requirements.txt

### 4️⃣ Set up environment variables
cp .env.example .env

## 🧠 Usage

### **Run the assistant directly from the terminal:**

python main.py --query "Evolución de la inteligencia artificial"

EThe assistant will:

    Retrieve relevant information from the web.

    Process and summarize it using an AI model.

    Return a structured and concise research report.

Optionally, results can be stored in .txt files or databases.

## 🧩 Project Structure

Ia-asistant-investigation/
│
├── main.py              # Entry point
├── tool.py              # Helper functions
├── requirements.txt     # Dependencies
├── .env.example         # Environment variable template
└── README.md            # Documentation


## 🧱 Roadmap
- Persistent session memory
- Database integration for contextual storage
- Multi-agent orchestration via Docker
- Optional web interface


#👨‍💻 Author

Martin (Matrinoza)
Systems Analysis Student | Python Developer | Linux Enthusiast
🔗 [GitHub](https://github.com/Matrinoza)

