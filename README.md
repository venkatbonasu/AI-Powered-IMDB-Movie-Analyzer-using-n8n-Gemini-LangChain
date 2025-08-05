# AI-Powered-IMDB-Movie-Analyzer-using-n8n-Gemini-LangChain
# 🎬 AI-Powered IMDB Movie Analyzer using n8n + Gemini + LangChain

This project demonstrates an AI-powered agent built in [n8n](https://n8n.io) that connects with **Google Gemini** (via LangChain) and **Google Sheets** to analyze and respond to movie-related queries like top-rated movies, filtering by year, and more.

---

## 🚀 Features

- 🔗 **Google Gemini Chat Model**: Used as the AI brain for conversational analysis.
- 📚 **LangChain Integration**: Enables context-aware chaining and memory.
- 📊 **Google Sheets**: Acts as a dynamic movie dataset backend.
- 🔍 **Query Capabilities**: Ask things like:
  - "Display top 5 movies by rating"
  - "Show movies released between 2000–2010"
- 🧠 **Memory Options**: Optional Redis or in-memory memory support via LangChain.

---

## 🛠️ Tech Stack

| Component        | Purpose                                  |
|------------------|------------------------------------------|
| n8n              | Workflow Automation Tool                 |
| Google Gemini    | Chat model for AI reasoning              |
| LangChain        | Agent interface with memory & prompts    |
| Google Sheets    | Data source for movie info               |
| (Optional) Redis | Chat memory for long-term context        |

---

