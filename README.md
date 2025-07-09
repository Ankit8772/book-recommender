# 📚 Semantic Book Recommender

A smart, emotion-aware book recommendation system built with **Python**, **Gradio**, and **Hugging Face Embeddings**, and deployed seamlessly on **Hugging Face Spaces**.
<img width="949" alt="image" src="https://github.com/user-attachments/assets/3f53ef54-d979-430e-9900-c2fede14ef95" />


---

## 🚀 Overview

The Semantic Book Recommender helps users find the most relevant books based on the **semantic meaning** of their query, along with their **emotional tone preferences** and **category choices** like Fiction, Non-fiction, Children, Adult, etc.

It uses:

- **Hugging Face Transformers** for local embeddings
- **LangChain** for text processing and vector search
- **Chroma DB** for storing embeddings
- **Gradio** for the interactive web interface

---

## 🧠 Features

✅ **Semantic Search** – Understands your natural language description  
✅ **Emotion Filtering** – Choose tones like *Happy*, *Sad*, *Suspenseful*, etc.  
✅ **Category Filtering** – Pick from categories like *Fiction*, *Nonfiction*, *Adult*, *Children*  
✅ **Kaggle Dataset** – Book metadata with emotional tags  
✅ **No API Keys Needed** – Uses open-source embedding models  
✅ **Deploys Easily** – Built for Hugging Face Spaces

---

## 📂 Dataset

The book dataset was sourced from **Kaggle**, and includes:

- ISBN, Title, Authors, Descriptions
- Simplified Categories (Fiction, Nonfiction, etc.)
- Emotion scores (Joy, Sadness, Anger, etc.)
- Thumbnail images

---

## 🔍 Tech Stack

| Component          | Tool/Library                     |
|-------------------|----------------------------------|
| Frontend UI       | [Gradio](https://gradio.app)     |
| Embeddings        | `all-MiniLM-L6-v2` (Hugging Face)|
| Vector DB         | Chroma (via `langchain_chroma`)  |
| Text Split/Loader | LangChain Community modules      |
| Hosting           | [Hugging Face Spaces](https://huggingface.co/spaces) |
| Language          | Python 3.10                       |

---

## 🧑‍💻 How to Use

1. **Enter a book description** — e.g., `"a story about redemption"`  
2. **Choose a category** — Fiction, Nonfiction, etc.  
3. **Pick an emotional tone** — Happy, Sad, Surprising, etc.  
4. **Click "Find Recommendations"**  
5. ✅ Get top books that best match your request with thumbnails and brief captions

---
