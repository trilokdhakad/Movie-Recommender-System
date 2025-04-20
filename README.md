# 🎬 Movie Recommendation System

This project recommends similar movies based on content-based filtering using the TMDB 5000 dataset. It includes a Jupyter notebook for data processing and model creation, and a Flask web app to view the final results and get predictions.

---

##  Files to Download

Before running the project, **download the following CSV files** from Kaggle:

- [`tmdb_5000_movies.csv`](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- [`tmdb_5000_credits.csv`](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

Place both files in the **project root directory**.

---

##  How It Works

1. The Jupyter notebook (`movie-recommendations.ipynb`) processes the data and builds a recommendation model.
2. It generates two `.pkl` files:
   - `movies.pkl`
   - `similarity.pkl`
3. These `.pkl` files are loaded by the Flask app (`app.py`) to serve real-time movie recommendations on a web interface.

---

## 🚀 Run the Project

### 1. Install dependencies

```bash
pip install -r requirements.txt
