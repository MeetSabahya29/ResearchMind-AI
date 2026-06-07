# 🔬 ResearchMind: Multi-Agent AI Research System

ResearchMind is an advanced, production-ready multi-agent AI research platform built using **LangChain** and **Streamlit**. The system coordinates specialized AI agents and chains—Search, Reader, Writer, and Critic—to automatically research any topic, scrape deep web resources, synthesize findings into a comprehensive markdown report, and provide critical evaluation feedback.

---

## 🚀 Features

- **🌐 Live Web Search Agent**: Queries the web dynamically using the Tavily API to fetch the most recent, relevant, and reliable snippets and URLs.
- **📄 Deep Reader Agent**: Dynamically selects the best resource from search results and scrapes full-text web pages while filtering out noise (scripts, styles, navbars, and footers).
- **✍️ Expert Writer Chain**: Structurally synthesizes compiled research data into a beautifully formatted, professional markdown report.
- **🧐 Critic Evaluation Chain**: Rigorously reviews the final report, scores it out of 10, highlights strengths, and suggests specific areas for improvement.
- **🎨 Custom Premium UI**: Features a sleek dark-mode custom-styled interface using Streamlit, complete with smooth visual pipeline progress indicators.
- **⬇️ Export Ready**: Download your generated comprehensive research reports instantly as standard `.md` files.

---

## 📂 Project Structure

The project follows a clean separation of concerns:
- **`app.py`**: The frontend user interface containing custom CSS styling and interactive execution pipeline handlers.
- **`agents.py`**: Configuration module for LangChain agents and core LLM chains powered by Mistral AI.
- **`tools.py`**: Custom execution tools including Tavily search wrappers and automated web scraping utilities via BeautifulSoup.
- **`pipeline.py`**: Backend workflow module allowing full execution of the multi-agent framework directly through the CLI/Terminal.
- **`requirements.txt`**: The comprehensive list of all required packages and ecosystem dependencies.

---

## 🛠️ Local Setup & Installation

Follow these steps to configure and run the project locally on your machine:

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_GITHUB_USERNAME/ResearchMind-AI.git](https://github.com/YOUR_GITHUB_USERNAME/ResearchMind-AI.git)
cd ResearchMind-AI