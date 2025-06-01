
# Personal-RAG

A Retrieval-Augmented Generation (RAG) demo app built with LangFlow, Streamlit, and LangChain.  
Integrates retrieval with language models to answer questions based on document data.

## Setup & Usage

```bash
# Clone the repo
git clone https://github.com/KarthikChekuri/Personal-RAG.git
cd Personal-RAG

# Create and activate conda environment with Python 3.10
conda create -n rag-app python=3.10
conda activate rag-app

# Install dependencies
pip install langflow streamlit langchain-community

# Run the app
streamlit run app.py

# Alternatively, launch LangFlow UI
langflow run
