# AI-Document-QnA-System

## About The Project

This project was built for the participation of ***Team Vanilla*** in the ***AI Tool Development Hackathon, sponsored by Mando***.
I have built a ***General-Purpose Document Question Answering System***
It can ingest documents in a wide range of formats and accurately answer user's questions based on Doc's content.
This Project is built using python in VS code as IDE
It uses streamlit module in python and streamlit cloud integrated with a github Repository for hosting the website

### Features

📄 Multi-format Document Support – Upload PDF, DOCX, PPTX, XLSX, PNG, JPG, CSV, JSON, TXT
🤖 AI-Powered Q&A – Ask any question related to the ingested content
📚 Contextual Answers – Answers supported with source references only
🌐 Web Interface – Easy-to-use frontend interaction 

### How it Works

Document Ingestion – The bot loads the uploaded docs and seperate it in chunks
Embedding Generation – Converts the document text into vector representations using Sentence Transformers
Indexing – Stores embeddings in a vector database that is FAISS
Query Handling – Converts user questions into vectors and finds the most relevant document chunks.
Answer Generation – Uses an LLM (Llama 4 Scout 17B 16E) to generate an answer based on retrieved context.

## Requirements
The project is built using the following Libraries/packages/modules in python:

streamlit
groq
faiss-cpu
numpy
pandas
pdfplumber
python-docx
python-pptx
easyocr
sentence-transformers
openpyxl

I have used ***GroqCloud*** which is an *cloud-based*, *open-source* Platfrom which provide ***API Keys*** various ***Large Language Models*** (LLMs) for free.
I have choosen ***Llama 4 Scout 17B 16E*** as my LLM model for this project.

## To-Do / Future Enhancements

## Acknowledgements 
[chat_GPT](https://chatgpt.com/)
[Youtube](https://www.youtube.com/)

## Contact
***Smail-*** md24b033@smail.iitm.ac.in

