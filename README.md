
# 🎬 Movie Recommender System

This is a content-based Movie Recommender System built using Python and Jupyter Notebook. It recommends similar movies based on user input using textual data like genres, keywords, and cast from the TMDB 5000 dataset.

---

## 📂 Project Structure
Movie_Recommender/
│
├── movie_recommender.ipynb # Jupyter notebook with code and analysis
├── tmdb_5000_movies.csv # Movie metadata
├── tmdb_5000_credits.csv # Cast and crew info
├── .gitignore # Git ignore file (optional)
└── README.md # Project documentation


---

## 🧠 Features

- Recommends top 5 similar movies using cosine similarity.
- Combines genres, keywords, cast, and crew into a single feature vector.
- Basic preprocessing using NLP (tokenization, stemming, lowercase normalization).
- Lightweight and fast for small to medium datasets.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (TF-IDF, Cosine Similarity)
- NLTK (for text processing)
- Jupyter Notebook

---

## 📊 Dataset

- Source: [TMDB 5000 Movie Dataset (Kaggle)](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Files used:
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie_recommender.git



📝 Example
If you enter: INCEPTION
It might recommend:
- Interstellar
- The Prestige
- The Matrix
- The Dark Knight
- Edge of Tomorrow

