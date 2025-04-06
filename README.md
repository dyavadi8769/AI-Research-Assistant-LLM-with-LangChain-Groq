# 🚀 AI Research Assistant with LangChain & Groq

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-FF6A00?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-00FF00?style=for-the-badge)

App url: https://searchenginellm-fpvveelpoptia4dfulhjfk.streamlit.app/

A powerful AI research assistant that combines web search, Wikipedia, and Arxiv research capabilities using LangChain agents and Groq's ultra-fast LLM inference.

## 🌟 Features

- **Multi-source knowledge retrieval** from:
  - Web search (DuckDuckGo)
  - Wikipedia articles
  - Arxiv research papers
- **Conversational interface** with chat memory
- **Transparent reasoning** with thought process visualization
- **Lightning-fast responses** powered by Groq's Llama3-8b
- **Easy API key configuration** via sidebar

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **LLM**: Groq (Llama3-8b-8192)
- **LangChain Tools**:
  - WikipediaQueryRun
  - ArxivQueryRun
  - DuckDuckGoSearchRun
- **Agent**: Zero-shot ReAct

## ⚙️ Commands to Setup Project on Local Machine

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dyavadi8769/AI-Research-Assistant-LLM-with-LangChain-Groq.git
   cd AI-Research-Assistant-LLM-with-LangChain-Groq
2.  **Create a virtual environment and activate it:**
    ```bash
    conda create -p env python==3.11 -y
    conda activate env/ 
3.  **Install the Required Dependecies:**
    ```bash
    pip install -r requirements.txt
4. **Run the app.py:**
    ```bash
    streamlit run app.py

# Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request.


# Author:

```bash
Author: Sai Kiran Reddy Dyavadi
Role  : Data Scientist
Email : dyavadi324@gmail.com
```

