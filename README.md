# 🧮 Text to Math Problem Solver & Data Search Assistant

This interactive **Streamlit application** empowers users to convert everyday language into **solvable math problems** and perform **factual searches** using **LangChain**, **Groq’s LLM (Gemma2-9b-It)**, and **Wikipedia**.

---

## 🚀 Features

- ✨ **Text-to-Math Reasoning**: Solves word-based math problems step-by-step with explanations.
- 📚 **Wikipedia Integration**: Provides detailed knowledge and summaries using Wikipedia API.
- 🧠 **Logical Thinking Tool**: Handles complex logic or reasoning-based questions using custom prompts.
- 🔢 **Calculator Tool**: Evaluates mathematical expressions with precision.
- 💬 **Chat Interface**: Engaging, chat-style Q&A using Streamlit.

---

## 🛠️ Tech Stack

- **[Streamlit](https://streamlit.io/)** – Frontend for interactive input/output
- **[LangChain](https://www.langchain.com/)** – Tool orchestration & chain creation
- **[Groq LLM (Gemma2-9b-It)](https://console.groq.com/)** – High-performance LLM
- **Wikipedia API Wrapper** – Data fetching from Wikipedia
- **LLMMathChain** – Handles and evaluates mathematical queries

---

## 🧠 Tools Integrated

| Tool Name        | Description                                                  |
|------------------|--------------------------------------------------------------|
| `Calculator`     | Evaluates pure mathematical expressions                      |
| `Wikipedia`      | Searches for general knowledge and factual information       |
| `Reasoning Tool` | Solves logic-based and natural language math problems        |

---

## 🖥️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/math-ai-assistant.git
   cd math-ai-assistant
2. **Install dependencies**
```bash
pip install -r requirements.txt
```
3. **Run the Streamlit app**
  ```bash

streamlit run app.py
```
## 🔐 Authentication
You’ll need a Groq API Key to use this app.

Get your API key from Groq Console

Paste it into the sidebar input when prompted in the app.

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for more information.

