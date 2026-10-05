# 🎬 Movie Recommender System

A content-based movie recommendation system built using Python, 
TF-IDF vectorization, cosine similarity, and Streamlit.

## 📌 Overview

This project recommends movies that are similar to a movie selected
by the user. The system uses movie metadata to create numerical
representations using TF-IDF and calculates similarity between movies.

## ✨ Features

- 🔍 Search movies using keywords
- 🎬 Browse movies by category
- 📋 Movie suggestions while searching
- 🎯 Content-based movie recommendations
- 📊 TF-IDF based feature representation
- 🔎 Cosine similarity for finding similar movies
- 🖼️ Movie poster display
- 🌐 Interactive Streamlit interface
- 🔗 Movie detail pages with recommendations

## 🧠 Recommendation Approach

The recommendation engine follows these steps:

1. Load and preprocess movie metadata.
2. Combine relevant movie features.
3. Convert text features into numerical vectors using TF-IDF.
4. Calculate cosine similarity between movies.
5. Find movies with the highest similarity scores.
6. Display the most relevant recommendations.

### Algorithm

**TF-IDF → Cosine Similarity → Top-N Recommendations**

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- TF-IDF Vectorizer
- Cosine Similarity
- Pickle

## 📂 Project Structure

```text
Movie-Recommendation/
│
├── app.py
├── main.py
├── df.pkl
├── indices.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── requirements.txt
├── .env
├── .gitignore
│
└── README.md
