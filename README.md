# 🎬 Movie Recommender System

A content-based movie recommender system built using Python and scikit-learn. This notebook demonstrates how to suggest similar movies based on a selected title using metadata like genre, cast, director, etc.

## 📌 Features
- Content-based recommendation using cosine similarity
- Uses movie metadata (genre, cast, director, etc.)
- Built with pandas, scikit-learn, and Python
- Simple and easy to understand notebook

## 🧠 How it works
1. Loads a dataset of movies with metadata
2. Combines key features into a single string
3. Vectorizes the combined features using CountVectorizer
4. Calculates similarity scores
5. Recommends top N similar movies

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Libraries: `pandas`, `sklearn`, `numpy`

### Run the Notebook
```bash
jupyter notebook
# Open and run `movie_recommender_system.ipynb`

