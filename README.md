# Documents-Q-A-with-GORQ-LLAMA3
"Ask Questions About Your Documents" is a Streamlit app powered by LangChain and Groq API. It enables users to query loaded PDF documents, leveraging embeddings for efficient retrieval and accurate answers based on contextual analysis. Ideal for document-intensive tasks in research and data analysis.

## Features
Load PDF documents from a specified directory.

Split documents into manageable chunks for processing.

Create vector embeddings for efficient document retrieval.

Ask questions and get accurate answers based on the context of the loaded documents.

View the most relevant document chunks related to your question

## Requirements
Python 3.8 or higher

Streamlit

LangChain and associated modules

Groq API key

dotenv for environment variable management

## Installation
**Clone the repository:**

  git clone https://github.com/manoranjan-30/Documents-Q&A-with-GORQ_LLAMA3.git
 
  cd Documents-Q&A-with-GORQ_LLAMA3

**Install dependencies:**

  pip install -r requirements.txt

**Set up environment variables:**

  Create a .env file in the root directory of the project.

**Add your LangChain API key to the .env file:**

  LANGCHAIN_API_KEY=your_api_key_here

  GROQ_API_KEY=your_groq_api_key

**Run the Streamlit application:**

 streamli run groq-llama3.py
