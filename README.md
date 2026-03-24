# Semantic Research Paper Search Engine

## 🚀 Overview

An AI-powered semantic search system that retrieves relevant research papers based on user queries.
Instead of keyword matching, this system uses **NLP embeddings and cosine similarity** to understand the meaning of queries and return the most relevant papers.

---

## 🧠 Features

* Semantic search for research topics
* Embedding-based paper retrieval
* FastAPI backend for search queries
* Top-K relevant paper results
* Efficient vector-based similarity search

---

## ⚙️ Tech Stack

* Python
* FastAPI
* Sentence Transformers
* Scikit-learn
* Pandas / NumPy

---

## 🔍 How It Works

1. Research papers (title + abstract) are processed
2. Text is converted into embeddings using a transformer model
3. Embeddings are stored as vectors
4. User query is converted into a vector
5. Cosine similarity is used to find closest papers
6. Top relevant papers are returned

---

## 📁 Project Structure

```
semantic-paper-search/
│
├── data/          # raw dataset (not pushed)
├── models/        # embeddings + metadata (not pushed)
├── engine/        # core logic
├── backend/       # FastAPI app
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```
git clone https://github.com/YOUR-USERNAME/semantic-paper-search.git
cd semantic-paper-search
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the API

```
uvicorn backend.main:app --reload
```

### 4. Open API docs

```
http://127.0.0.1:8000/docs
```

---

## 🔎 Example Query

```
machine learning
```

Returns top 10 relevant research papers based on semantic similarity.

---

## 📌 Future Improvements

* Add frontend interface
* Implement vector database (FAISS)
* Add filtering by category/year
* Improve ranking and relevance

---


