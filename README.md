# 🏛️ PU Senate Law Chatbot

This project is an intelligent chatbot system designed to answer queries from the **Panjab University Senate Law Document** using Natural Language Processing (NLP) and deep learning techniques. It enables users to semantically search and retrieve relevant sections from the official legal document using state-of-the-art embedding techniques and vector similarity search.

---

## 🧠 Key Features

- Extracts and processes content from the university's Senate Law PDF
- Splits legal text into logically structured chunks for better understanding
- Generates embeddings using both character-level encoding and transformer-based models (MiniLM)
- Stores text embeddings in a FAISS index for fast similarity search
- Supports semantic search and lays the foundation for chatbot functionality

---

## 🛠 Technologies Used

- Python  
- NLP & Deep Learning  
- Transformers (`sentence-transformers`)  
- FAISS (Facebook AI Similarity Search)  
- LangChain  
- PyMuPDF  
- EDA (Exploratory Data Analysis)

---

## 🗂 Project Workflow

1. **PDF Parsing** – Extracted raw text from the Senate Law document using PyMuPDF  
2. **Text Splitting** – Divided long legal text into meaningful, searchable chunks using LangChain  
3. **Embeddings Generation** – Created semantic embeddings using pretrained transformer models  
4. **Vector Indexing** – Stored embeddings using FAISS for high-speed retrieval  
5. **Semantic Search** – Matched user queries with most relevant chunks in the document

---

## 🔍 Example Use Case

- A student can ask, “What is the composition of the Senate?”  
- The system retrieves the most relevant clause or paragraph from the Senate Law PDF using semantic similarity

---

## 📈 Future Improvements

- Add a conversational frontend interface (chatbot or web UI)  
- Integrate OpenAI or other LLM APIs for dynamic answers  
- Support multi-document legal corpora  
- Add Q&A and summarization modules

---

## 👩‍💻 Author

**Akshita Nandal**  
B.E. CSE, UIET Panjab University  
Email: akshitanandal@gmail.com  
LinkedIn: https://www.linkedin.com/in/akshita-480a69250
GitHub: https://github.com/axi-ta-n

---

## ⭐️ Support

If you find this project useful or inspiring, please consider giving it a ⭐️ on GitHub!
