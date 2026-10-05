# 🏥 End-to-End Medical RAG Chatbot

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

## 📌 Project Overview
An **End-to-End Medical Conversational AI** powered by Retrieval-Augmented Generation (RAG). Medical documentation is processed into vector embeddings, stored in a Pinecone index, and queried dynamically using HuggingFace models and LangChain to provide accurate health explanations via a web user interface.

## ✨ Key Features
- **RAG Architecture**: Document chunking, vector indexing, and context retrieval to prevent LLM hallucinations.
- **Vector Search Engine**: Pinecone indexing with HuggingFace `all-MiniLM-L6-v2` embeddings.
- **Flask GUI Interface**: Interactive web frontend for medical Q&A chat.

## 🛠️ Tech Stack
| Category | Technology |
| :--- | :--- |
| **Backend & Frameworks** | Python, Flask, LangChain |
| **Embeddings & Vector Store** | HuggingFace SentenceTransformers, Pinecone DB |
| **Frontend** | HTML5, CSS3, JavaScript |

## 📁 Project Structure
```text
├── README.md
├── app.py
├── data/
│   └── api.txt
├── key
├── key.pub
├── requirements.txt
├── setup.py
├── src/
│   ├── __init__.py
│   ├── helper.py
│   └── prompt.py
├── ssh
├── ssh.pub
├── static/
│   └── styles.css
├── store_index.py
├── template.py
├── templates/
│   ├── 9193824.png
│   └── index.html
├── test.py
├── trials.ipynb
└── vercel.json
```

## ⚙️ Setup & Execution
```bash
pip install -r requirements.txt
python store_index.py
python app.py
```
Open `http://localhost:8080` in your web browser.

## 👤 Author
Developed as part of my GenAI & LLM engineering portfolio.
