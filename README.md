# Vector Store Databases

This repository contains hands-on practice and examples for **Vector Store Databases** used in **Generative AI, NLP, and RAG (Retrieval-Augmented Generation)** applications.

The main focus of this repository is **ChromaDB** and its integration with **LangChain**.

---

## 📌 What is a Vector Store?

A **Vector Store** is a database designed to store and search **vector embeddings**.

In Generative AI applications, text is converted into numerical vectors called **embeddings**. These vectors allow us to find documents or text that are semantically similar to a user's query.

Vector stores are commonly used in:

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Question Answering
- Document Search
- Recommendation Systems
- AI Chatbots

---

## 🧠 Topics Covered

This repository mainly focuses on:

- Vector embeddings
- Vector databases
- ChromaDB
- Creating collections
- Adding documents and embeddings
- Storing and retrieving vectors
- Similarity search
- Metadata
- Persistent vector storage
- ChromaDB with LangChain
- Using vector stores in RAG applications

---

## 📂 Repository Structure

```text
Vector_Store_Databases/
│
├── Chroma_db/
│   └── ChromaDB related files and data
│
├── Chroma_DB.ipynb
│   └── ChromaDB concepts and practical examples
│
├── langchain_chroma.ipynb
│   └── ChromaDB integration with LangChain
│
└── README.md
```

---

## 🔹 ChromaDB

**ChromaDB** is an open-source vector database designed for AI applications.

It can store:

- Documents
- Embeddings
- Metadata
- IDs

It allows us to perform similarity searches and retrieve the most relevant information based on a query.

A simplified workflow is:

```text
Documents
    ↓
Text Chunking
    ↓
Embedding Model
    ↓
Vector Embeddings
    ↓
ChromaDB
    ↓
Similarity Search
    ↓
Relevant Documents
```

---

## 🔹 ChromaDB Notebook

### `Chroma_DB.ipynb`

This notebook contains practical work with **ChromaDB**.

It helps understand concepts such as:

- Creating a ChromaDB database
- Creating collections
- Adding documents
- Generating/storing embeddings
- Adding metadata
- Querying stored documents
- Similarity search
- Retrieving relevant results

---

## 🔹 LangChain + ChromaDB

### `langchain_chroma.ipynb`

This notebook focuses on using **ChromaDB with LangChain**.

LangChain provides convenient abstractions for connecting vector stores with the rest of a GenAI/RAG pipeline.

Typical workflow:

```text
Documents
    ↓
Document Loader
    ↓
Text Splitter
    ↓
Embeddings
    ↓
ChromaDB
    ↓
Retriever
    ↓
LLM
    ↓
Final Answer
```

This is an important part of building a **RAG application**.

---

## 💾 Persistent Storage

The `Chroma_db` folder is used for working with ChromaDB storage.

Persistent storage allows vectors and related data to remain available after the Python program or notebook is closed.

This is useful when building real applications because we don't need to recreate the vector database every time.

---

## 🛠️ Technologies Used

- **Python**
- **ChromaDB**
- **LangChain**
- **Vector Embeddings**
- **Jupyter Notebook**
- **Generative AI**
- **RAG**

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/laxmankhedkar/Vector_Store_Databases.git
```

Go to the project directory:

```bash
cd Vector_Store_Databases
```

Install the required packages:

```bash
pip install chromadb langchain langchain-chroma
```

For working with Jupyter Notebook:

```bash
pip install notebook
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🎯 Learning Objectives

After working through this repository, you should be able to understand:

- What a vector database is
- Why vector databases are required in GenAI applications
- What embeddings are
- How ChromaDB stores vector data
- How similarity search works
- How to work with ChromaDB collections
- How to store metadata with documents
- How persistent vector storage works
- How to connect ChromaDB with LangChain
- How vector stores fit into a RAG pipeline

---

## 🚀 Real-World Use Case

Vector stores are an important component of modern **RAG applications**.

For example, a company can store its internal documents in a vector database.

When a user asks:

```text
"What is the company's leave policy?"
```

The application can:

1. Convert the question into an embedding.
2. Search the vector database.
3. Find the most relevant document chunks.
4. Pass those chunks to an LLM.
5. Generate an answer based on the retrieved information.

This helps an LLM answer questions using **external/private knowledge**.

---

## 🔗 Related Concepts

This repository connects with other important GenAI concepts:

```text
Document Loaders
       ↓
Text Splitters
       ↓
Embeddings
       ↓
Vector Store
       ↓
Retriever
       ↓
RAG
       ↓
LLM
```

Understanding this complete flow is useful for building practical **GenAI and RAG applications**.

---

## 📌 Future Improvements

Possible improvements for this repository:

- Add more ChromaDB examples
- Compare ChromaDB with other vector databases
- Add similarity search examples
- Add metadata filtering examples
- Build a complete RAG application using ChromaDB
- Add different embedding models
- Compare different retrieval strategies

---

## 👨‍💻 Author

**Laxman Khedkar**

Data Scientist & ML Engineer | Python | SQL | Machine Learning | NLP | LLMs | RAG | Generative AI

GitHub: [@laxmankhedkar](https://github.com/laxmankhedkar)

---

## ⭐ If You Find This Useful

If this repository helps you understand **Vector Stores, ChromaDB, or RAG**, consider giving it a ⭐ on GitHub.
