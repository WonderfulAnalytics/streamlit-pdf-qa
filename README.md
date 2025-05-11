# PDF Question Answering App using GPT-4 and LangChain

This Streamlit application allows you to upload a PDF and ask questions about its content.  
It uses OpenAI's GPT-4 and LangChain's Retrieval-Augmented Generation (RAG) pipeline to return accurate answers along with source page references.

---

## Features

- Upload any PDF file
- Ask questions based on its content
- Get answers powered by GPT-4
- View the source text and page numbers used
- Clean and interactive UI using Streamlit

---

## Tech Stack

- [LangChain](https://www.langchain.com/)
- [OpenAI GPT-4](https://platform.openai.com/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Streamlit](https://streamlit.io/)
- Python 3.9+

---

## How to Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/WonderfulAnalytics/streamlit-pdf-qa.git
cd streamlit-pdf-qa

## Create a virtual environment

python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

## Install dependencies

pip install -r requirements.txt

## Set your OpenAI API key
OPENAI_API_KEY=your_openai_api_key_here

## Run the app
streamlit run app.py

