# 📚 NLP Project – Word2Vec on Custom Text Corpus

This project demonstrates how to train a **Word2Vec model** using the `gensim` library on a custom text dataset.  
The dataset is tokenized, processed, and then used to learn word embeddings that capture semantic similarity between words.

---

## 🚀 Features
- Loads multiple text files from a `data/` folder.  
- Preprocesses text:
  - Sentence tokenization (`nltk.sent_tokenize`)  
  - Word tokenization & cleaning (`gensim.simple_preprocess`)  
- Builds a **corpus** of tokenized sentences.  
- Trains a **Word2Vec model** with:
  - Context window = 10  
  - Minimum word frequency = 2  
- Queries word similarity (e.g., most similar to `"daenerys"`).

---

## 📂 Project Structure
project on nlp.ipynb # Jupyter Notebook
data/ # Folder containing text files
README.md # Documentation
