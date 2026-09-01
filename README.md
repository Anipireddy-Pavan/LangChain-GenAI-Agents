# LangChain GenAI Agents

A progressive, notebook-based exploration of core **LangChain** concepts — from basic setup through model integration, tool calling, message handling, structured outputs, and middleware. Built to understand how LangChain applications are structured internally, from the ground up.

---

## 📌 Overview

This repository walks through the foundational building blocks of LangChain in a structured sequence, with each notebook building on concepts from the one before it. Rather than jumping straight to a finished application, the goal is to understand **how and why** each LangChain component works before combining them into full agentic systems.

---

## 🧭 Learning Path

```
1. LangChain Intro
        │
        ▼
2. Model Integration
        │
        ▼
3. Tools
        │
        ▼
4. Messages
        │
        ▼
5. Structured Output
        │
        ▼
6. Middleware
```

---

## 📓 Notebooks

| # | Notebook | Focus |
|---|---|---|
| 1 | `1-langchainintro.ipynb` | LangChain fundamentals — core concepts and setup |
| 2 | `2-modelintegration.ipynb` | Integrating LLMs (chat models, providers, configuration) |
| 3 | `3-tools.ipynb` | Defining and calling tools with LangChain |
| 4 | `4-messages.ipynb` | Message types and conversation handling |
| 5 | `5-structuredoutput.ipynb` | Getting structured, schema-validated responses from LLMs |
| 6 | `6-middleware.ipynb` | Middleware patterns for intercepting and controlling agent execution |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core language |
| LangChain | LLM application framework |
| Jupyter Notebook | Interactive experimentation |
| uv | Python dependency and environment management |

---

## 📁 Project Structure

```
LangChain-GenAI-Agents/
│
├── 1-langchainintro.ipynb
├── 2-modelintegration.ipynb
├── 3-tools.ipynb
├── 4-messages.ipynb
├── 5-structuredoutput.ipynb
├── 6-middleware.ipynb
├── src/
│   └── langchainupdated/
├── pyproject.toml
├── requirements.txt
├── uv.lock
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

```bash
git clone https://github.com/Anipireddy-Pavan/LangChain-GenAI-Agents.git
cd LangChain-GenAI-Agents

# Using uv
uv venv
.venv\Scripts\activate    # Windows
uv sync

# Or using pip
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file for any required API keys (model provider dependent):

```
MODEL_API_KEY=your_api_key_here
```

Never commit `.env` files or API keys to GitHub.

---

## ▶️ Running the Notebooks

```bash
jupyter notebook
```

Open notebooks in order (1 → 6) for the intended learning progression.

---

## 📚 Learning Outcomes

Working through this repository builds practical understanding of:

- LangChain's core architecture and abstractions
- Integrating and configuring chat models
- Defining and invoking tools
- Managing conversation messages and history
- Enforcing structured, schema-validated LLM outputs
- Using middleware to control and inspect agent execution

---

## 👨‍💻 Author

**Pavan Anipireddy**
Data Science | Generative AI | LangChain | Python | SQL
GitHub: [Anipireddy-Pavan](https://github.com/Anipireddy-Pavan)

---

## 📄 License

This repository is intended for educational and portfolio purposes.
