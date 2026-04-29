# 🤖 Autonomous AI Agent using LangChain

## 🚀 Overview

This project implements an **Autonomous AI Agent** built using LangChain that can perform **multi-step reasoning and tool-based decision making**.

The agent can dynamically decide when to use external tools like search APIs and weather APIs to answer user queries.

---

## 🎯 Features

* 🧠 Multi-step reasoning using LLM
* 🔧 Tool-based architecture (Search, APIs)
* 🌐 Real-time information retrieval
* 🤖 Dynamic decision-making agent
* 💬 Handles complex user queries

---

## 🧠 How It Works

1. User provides a query
2. LLM analyzes intent
3. Agent decides whether to use tools
4. External APIs are invoked if needed
5. Final response is generated

---

## 🛠️ Tech Stack

* **Language:** Python
* **Framework:** LangChain
* **LLM:** Groq 
* **Tools:** DuckDuckGo Search, Weather API

---

## 📂 Project Structure

LangChain_Agent/
│── agent/ # Agent logic
│── tools/ # External tools
│── main.py # Entry point
│── requirements.txt

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/PiYusH9805/langchain-agent.git
cd langchain-agent
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the project

```bash
python main.py
```

---

## 📸 Future Improvements

* Add memory (chat history)
* Integrate more tools (database, APIs)
* Deploy as web application
* Upgrade to LangGraph workflow

---

## 👨‍💻 Author

**Piyush Sharma**
GitHub: https://github.com/PiYusH9805

---

## 📜 License

This project is for educational purposes.
