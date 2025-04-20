# AI-Document-QnA-System

## About The Project

This project was built for the participation of ***Team Vanilla*** in the ***AI Tool Development Hackathon, sponsored by Mando***.<br>
I have built a ***General-Purpose Document Question Answering System***<br>
It can ingest documents in a wide range of formats and accurately answer user's questions based on Doc's content.<br>
This Project is built using python in visual studio code as IDE<br>
It uses streamlit module in python and streamlit cloud integrated with a github Repository for hosting the website<br>

### Features

📄 Multi-format Document Support – Upload PDF, DOCX, PPTX, XLSX, PNG, JPG, CSV, JSON, TXT <br>
<br>
🤖 AI-Powered Q&A – Ask any question related to the ingested content <br>
<br>
📚 Contextual Answers – Answers supported with source references only <br>
<br>
🌐 Web Interface – Easy-to-use frontend interaction <br>
<br>

### How it Works

Document Ingestion – The bot loads the uploaded docs and seperate it in chunks.<br>
<br>
Embedding Generation – Converts the document text into vector representations using Sentence Transformers.<br>
<br>
Indexing – Stores embeddings in a vector database that is FAISS.<br>
<br>
Query Handling – Converts user questions into vectors and finds the most relevant document chunks.<br>
<br>
Answer Generation – Uses an LLM (Llama 4 Scout 17B 16E) to generate an answer based on retrieved context.<br>
<br>

## Requirements
<br>
The project is built using the following Libraries/packages/modules in python:
<br>
streamlit<br>
groq<br>
faiss-cpu<br>
numpy<br>
pandas<br>
pdfplumber<br>
python-docx<br>
python-pptx<br>
easyocr<br>
sentence-transformers<br>
openpyxl<br>
<br>
I have used GroqCloud which is an cloud-based, open-source Platfrom which provide API Keys various Large Language Models (LLMs) for free.<br>
I have choosen Llama 4 Scout 17B 16E as my LLM model for this project.<br>
<br>

## Procedure for running it Locally
1) Download the latest version of python, you can either use IDLE or VS code.<br>
<br>
2) Get Pip in CMD and download all the Libraries/packages/modules mentioned in requirements.<br>
<br>
3) GroqCloud Setup-<br>
   go to (https://console.groq.com/login and Log in<br>
   go to (https://console.groq.com/keys and create an API key<br>
   go to (https://console.groq.com/playground and select a LLM model<br>
<br>
4) Copy the python code (Main_Script.py) from this repository and save it in a folder<br>
<br>
5) Use the previously generated API key and paste it at its designated place in code<br>
<br>
6) Run the code, after few seconds, it will ask for file_path, now you are good to go!<br>
<br>
7) Make sure that the file you want to load is present in the root directory of the folder same as your python code folder<br>

   
## To-Do / Future Enhancements
<br>
Due to time constraint, I was unable to add following features-<br>
<br>
link crawler<br>
processing images within document of another format<br>
<br>

## Acknowledgements 
[chat_GPT](https://chatgpt.com/)<br>
[Youtube](https://www.youtube.com/)<br>
<br>
## Contact
Smail- md24b033@smail.iitm.ac.in

