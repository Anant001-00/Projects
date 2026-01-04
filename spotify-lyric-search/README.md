# Spotify Lyric Search (Machine Learning Project)

## Overview
This project is a Machine Learning–based lyric identification system.  
Given a small snippet of song lyrics as input, the system predicts the **song title** and **artist name** by finding the most similar lyrics from a Spotify songs dataset using NLP techniques.

---

## Problem Statement
Identify the correct song and artist when a user provides a short lyric snippet.

---

## Approach
1. Loaded a Spotify lyrics dataset containing song titles, artists, and lyrics  
2. Preprocessed lyrics by converting text to lowercase, removing punctuation, numbers, and stopwords  
3. Converted lyrics into numerical vectors using **TF-IDF**  
4. Used **Cosine Similarity** to match the input snippet with the closest song  
5. Returned the most similar song and artist  

---

## Technologies Used
- Python 3  
- Pandas  
- NLTK  
- Scikit-learn  
- Jupyter Notebook  

---

## Installation

### Prerequisites
- Python 3.x  
- Jupyter Notebook (Anaconda recommended)

### Install Required Libraries
```bash
pip install pandas nltk scikit-learn
