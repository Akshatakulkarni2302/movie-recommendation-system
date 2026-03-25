# 🎬 Movie Recommendation System

## 📌 Project Overview

This project is a machine learning-based movie recommendation system that suggests similar movies based on user selection.

It uses content-based filtering with cosine similarity to recommend top 5 similar movies.

---

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit

---

## 📂 Project Files

* app.py → Streamlit user interface
* movie_recommender.py → Data preprocessing and model creation
* requirements.txt → Required libraries

---

## ⚙️ How It Works

1. Dataset is loaded and cleaned
2. Important features like genres, overview, and keywords are combined
3. Text data is converted into vectors
4. Cosine similarity calculates similarity between movies
5. Top 5 similar movies are recommended

---

## ▶️ Run Project

### Install libraries

pip install -r requirements.txt

### Generate model files locally

python movie_recommender.py

### Run Streamlit app

python -m streamlit run app.py

---

## 📌 Dataset

Dataset used: TMDB 5000 Movie Dataset from Kaggle.

Large dataset and generated pickle files are excluded from GitHub due to file size limits.

---

## 📌 Output

Select a movie from dropdown and get top 5 recommended movies instantly.

---

## 🎯 Future Improvements

* Add movie posters
* Add TMDB API integration
* Add rating filter
* Deploy online
