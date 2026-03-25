# M25CSE024-A2

## Description
This repository contains solutions for Assignment 2, covering two major problems in Natural Language Processing and Deep Learning.

### Problem 1: Learning Word Embeddings from IIT Jodhpur Data
- Data collection and preprocessing from IIT Jodhpur sources  
- Training Word2Vec models (CBOW and Skip-gram)  
- Semantic analysis using cosine similarity  
- Analogy tasks  
- Visualization using PCA / t-SNE and WordCloud  

### Problem 2: Character-Level Name Generation using RNN Variants
- Dataset of Indian names  
- Implementation of RNN from scratch  
- Training and generating names  
- Evaluation using qualitative outputs  

---

## Requirements

The project requires the following Python libraries:

- torch  
- numpy  
- matplotlib  
- scikit-learn  
- wordcloud  

### Built-in libraries used:
- os  
- random  
- re  
- collections  

---

## Installation

Install all dependencies using:

pip install torch numpy matplotlib scikit-learn wordcloud

---

## How to Run

### Option 1: Using Google Colab
1. Open the notebooks in Google Colab:
   - Problem1.ipynb  
   - Problem2.ipynb  

2. Click **Runtime → Run all**  

3. Ensure dataset is available (see Dataset section)

---

### Option 2: Running Locally
1. Clone the repository:

git clone https://github.com/Priya-Kumari-Chourasia/M25CSE024-A2.git  

2. Navigate to the project folder:

cd M25CSE024-A2  

3. Install dependencies:

pip install torch numpy matplotlib scikit-learn wordcloud notebook  

4. Run Jupyter Notebook:

jupyter notebook  

5. Open and run:
- Problem1.ipynb  
- Problem2.ipynb  

---

## Dataset

### Problem 1:
- Text data collected from IIT Jodhpur sources  
- Preprocessed using tokenization, lowercasing, and noise removal  

### Problem 2:
- File: word_embed/TrainingNames.txt  
- Contains training names used for RNN model  

---

## Files
- Problem1.ipynb → Word2Vec training and analysis  
- Problem2.ipynb → RNN-based name generation  
- word_embed/TrainingNames.txt → Dataset  

---

## Results

### Problem 1:
- Learned meaningful word embeddings  
- Nearest neighbor and analogy analysis  
- Visualization shows semantic clustering  

### Problem 2:
- RNN generates realistic names  
- Outputs improve with training  

---

## Author
Priya Kumari
