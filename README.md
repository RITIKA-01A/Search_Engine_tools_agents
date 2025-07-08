# 🔍 AI Search Assistant – Arxiv, Wikipedia & DuckDuckGo
## This is a Streamlit-powered AI assistant that takes user input and intelligently searches across:

- 📚 Arxiv for scientific papers

- 🌐 Wikipedia for general knowledge

- 🦆 DuckDuckGo for web search

It returns the most relevant answer using these sources.

# 📁 Project Structure
```
├── .env                  # Environment variables (API keys)
├── .gitignore            # Files to ignore in Git
├── app.py                # Main Streamlit application
├── requirements.txt      # Python dependencies

```

 # Features
- ✨ Conversational interface via Streamlit

- 🔍 Search across Arxiv, Wikipedia, and DuckDuckGo

- 📡 Uses LangChain tools & retrievers

- 🧠 Intelligent source selection for best answer

- 🗃️ Maintains session state for message history
  
# 🛠️ Installation
## Clone the repo:
```
git clone https://github.com/yourusername/ai-search-assistant.git
cd ai-search-assistant
```
## Create virtual environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```
## Install dependencies:
```
pip install -r requirements.txt
```
## Set up .env file:
```
GROQ_API_KEY=your_actual_key_here
```
## ▶️ Run the App
```
streamlit run app.py
```
