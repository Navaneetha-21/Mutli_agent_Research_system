# 🤖 Multi-Agent AI Research System

A fully autonomous **Multi-Agent AI Research System** built using LangChain that mimics advanced research workflows.
The system can **search the web, scrape content, generate structured reports, and critically evaluate outputs** — all in an automated pipeline.

---

## 🚀 Features

* 🔍 **Autonomous Web Search** using Tavily API
* 🌐 **Intelligent Web Scraping** with BeautifulSoup
* 🧠 **Multi-Agent Architecture**

  * Search Agent
  * Reader Agent
* ✍️ **AI Research Report Generation**
* 🧪 **Automated Critic System** (self-evaluation & scoring)
* 🔄 **End-to-End Pipeline Orchestration**
* 💻 **Interactive UI** built with Streamlit

---

## 🏗️ System Architecture

The system is designed as a pipeline of specialized agents:

1. **Search Agent**
   Finds relevant web resources using Tavily API

2. **Reader Agent**
   Extracts meaningful content from URLs

3. **Writer Chain**
   Generates structured research reports

4. **Critic Chain**
   Evaluates report quality and provides feedback

5. **Pipeline Orchestrator**
   Manages shared state and coordinates workflow

---

## ⚙️ Tech Stack

* **Python**
* **LangChain**
* **OpenRouter (LLM API)**
* **Tavily API (Search)**
* **BeautifulSoup (Scraping)**
* **Streamlit (UI)**

---

## 📂 Project Structure

```
├── agents.py          # Agent definitions (Search & Reader)
├── tools.py           # Web search & scraping tools
├── pipeline.py        # Main orchestration logic
├── app.py             # Streamlit UI
├── requirements.txt   # Dependencies
├── .gitignore
└── README.md
```

---

## 🔧 Setup & Installation

### 1. Clone the repository

```
git clone https://github.com/yourusername/multi-agent-research-ai.git
cd multi-agent-research-ai
```

### 2. Create virtual environment

```
python -m venv .venv
.venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```
OPENAI_API_KEY=your_openrouter_api_key
OPENAI_BASE_URL=https://openrouter.ai/api/v1
TAVILY_API_KEY=your_tavily_api_key
```

---

## ▶️ Running the Project

### Run pipeline (CLI)

```
python pipeline.py
```

### Run Streamlit UI

```
streamlit run app.py
```

---

## 🧪 Example Workflow

1. User enters a research topic
2. Search Agent finds relevant sources
3. Reader Agent extracts content
4. Writer generates structured report
5. Critic evaluates and scores the report

---

## 📊 Sample Output

* Structured research report
* Key insights and findings
* Source references
* Quality score and feedback

---

## 🎯 Use Cases

* Academic research assistance
* Automated content generation
* Market research analysis
* AI-powered knowledge systems

---

## ⚠️ Important Notes

* Do **not commit your `.env` file** (API keys must remain private)
* Ensure API keys are valid before running
* Some websites may block scraping requests

---

## 🌟 Future Improvements

* Memory-enabled agents
* Multi-step reasoning workflows
* Better scraping (headless browser)
* Advanced UI enhancements

---

## 👨‍💻 Author

**Navaneetha**
Final Year Engineering Student | Aspiring AI Engineer
---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
