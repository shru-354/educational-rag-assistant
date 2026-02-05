# 📘 Educational RAG Assistant

An AI-powered Educational Content Assistant built using **Retrieval-Augmented Generation (RAG)**.  
This system helps students by answering questions using uploaded study materials such as PDFs, notes, and textbooks.

---

## 📌 Project Overview

The Educational RAG Assistant allows users to:
- Upload educational documents
- Ask questions related to the content
- Get accurate answers based on the uploaded material

It combines document retrieval with AI-generated responses to improve learning.

---

## 🚀 Features

- Upload and process PDF/Text files
- Semantic search using embeddings
- AI-powered question answering
- Fast and relevant responses
- Easy-to-use interface

---

## 🛠️ Technologies Used

- Python
- LangChain
- FAISS / ChromaDB (Vector Database)
- OpenAI / HuggingFace Model
- Streamlit / Flask (Frontend)
- GitHub (Version Control)

---

## 📂 Project Structure

```
educational-rag-assistant/
│
├── data/           # Uploaded documents
├── embeddings/     # Vector storage
├── app.py          # Main application
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/shru-354/educational-rag-assistant.git
cd educational-rag-assistant
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python app.py
```

OR (if using Streamlit):

```bash
streamlit run app.py
```

---

## 🧠 How It Works (RAG Architecture)

1. User uploads documents
2. Text is converted into embeddings
3. Stored in vector database
4. User asks a question
5. Relevant content is retrieved
6. AI generates final answer

---

## 🎯 Use Case

- Students preparing for exams
- Teachers creating study material
- Self-learning learners
- Research assistance

---

## 🌟 Unique Feature

- Personalized answers based on user-uploaded notes
- Supports multiple documents
- Improves accuracy using RAG technique

---

## 📈 Future Improvements

- Voice-based queries
- Multi-language support
- Mobile app version
- User login system
- Cloud deployment

---

## 👩‍💻 Author

**Shruti**  
B.Tech CSE Student  
GitHub:https://github.com/shru-354/educational-rag-assistant

---

## 📜 License

This project is created for educational purposes.
Free to use and modify.
