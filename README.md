# 🧠 Sentence Embedding & Semantic Similarity

This project demonstrates how to convert sentences into numerical **embeddings** and measure the **semantic similarity** between sentences using Python.

## 📌 Project Description

Sentence embeddings represent the meaning of sentences as numerical vectors.
This project uses the **Sentence Transformers** library to generate embeddings and **Cosine Similarity** to compare the meaning of different sentences.

The program identifies sentences that have a similarity score greater than **0.5**.

## 🛠️ Technologies Used

* Python
* Sentence Transformers
* Scikit-learn
* `all-MiniLM-L6-v2`
* Cosine Similarity

## ⚙️ How It Works

```text
Input Sentences
       ↓
Sentence Transformer Model
       ↓
Generate Embeddings
       ↓
Calculate Cosine Similarity
       ↓
Display Similar Sentences
```

## 📚 Example Sentences

The project uses sentences related to:

* Books and reading
* Movies
* Artificial Intelligence
* Machine Learning
* Deep Learning
* Python
* Weather

## 🔧 Installation

Install the required libraries using:

```bash
pip install sentence-transformers scikit-learn
```

## ▶️ How to Run

Open the project folder in VS Code and run:

```bash
python embedding.py
```

> Replace `embedding.py` with your actual Python file name if it is different.

## 📊 Output

The program displays:

1. Total number of sentences
2. Embedding dimension
3. Generated embeddings
4. Pairs of semantically similar sentences
5. Similarity score for each pair

Example:

```text
Total number of sentences: 8
Embedding dimension: 384

--- Semantic Similarity ---

Sentence 1: I love reading books.
Sentence 2: I enjoy reading novels.
Similarity: 0.xxxx
```

## 🧮 Cosine Similarity

Cosine similarity measures how similar two vectors are based on the angle between them.

A score closer to **1** indicates higher similarity, while a score closer to **0** indicates lower similarity.

## 🎯 Applications

Sentence embeddings and semantic similarity are useful in:

* Search engines
* Chatbots
* Recommendation systems
* Text classification
* Duplicate question detection
* Document similarity
* Natural Language Processing (NLP)

## 👩‍💻 Author

**Thansila Begam F**

B.Sc Computer Science & Artificial Intelligence
