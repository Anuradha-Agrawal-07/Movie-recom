# 🎬 Magic Movie Recommender 🍿

Welcome to Magic Movie Recommender, an intelligent movie recommendation system built using Streamlit and powered by TF-IDF and cosine similarity! Discover movies you'll ❤️ based on your favorites!


**Try it live**: https://movie-recom-priv.onrender.com/

---

# 🚀 Features
🎯 Personalized Recommendations based on movie overview, genres, cast, and director.

🔍 Search & Select any movie from the TMDB dataset.

🔥 Most Popular Movies section for quick picks.

🎲 "I'm Feeling Lucky" mode to explore something random.

🧰 Genre & Release Year Filters to fine-tune your movie suggestions.

🎨 Beautiful glassmorphism-style UI for a slick, modern look.

⚡ Fast performance using cached TF-IDF similarity calculations.

---

# 📁 Dataset
The project uses the TMDB 5000 Movie Dataset, which includes:
(You can download it from here)
(https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
tmdb_5000_movies.csv

tmdb_5000_credits.csv
Make sure both files are in the same directory as your script.

---

# 🧑‍💻 How It Works
Preprocessing:
Parses genres, top 3 cast members, and director from JSON-like fields.
Combines these with the overview to form a metadata string.

TF-IDF Vectorization:
Uses TfidfVectorizer from scikit-learn to convert metadata into feature vectors.

Similarity Matching:
Computes cosine similarity between all movies.
Finds top 5 similar movies for any given selection.

Filtering:
Apply optional filters like genre and release year.

---

# 🛠️ Tech Stack

- **Python**
- **pandas**, **scikit-learn**, **NumPy**
- **TF-IDF Vectorizer**, **Cosine Similarity**
- **Streamlit** for Frontend
- **Deployed** on Render 

---

## 📊 Dataset

- **TMDB 5000 Movies & Crew Dataset**
  - Used fields: *title, overview, popularity, release_date, genres, cast, crew*
  - Processed and vectorized for similarity comparison
    
---


## 📌 Note

The source code is **not included** in this public repository. The live version is accessible for demonstration and testing purposes.

---

## 🙋‍♀️ Author

**Anuradha Agrawal**  
[LinkedIn Profile] www.linkedin.com/in/anuradha-agrawal-739022321

## ✨ Feedback

Have suggestions or want to collaborate? Feel free to reach out via LinkedIn!

## 🙌 Acknowledgments
TMDB for the dataset

Streamlit for the awesome web app framework





