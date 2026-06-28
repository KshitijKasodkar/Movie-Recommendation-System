# Movie-Recommendation-System
An AI-powered movie recommendation system using NLP (TF-IDF), FastAPI, Streamlit, and TMDB API.

# 🎬 Movie Recommendation System

An AI-powered movie recommendation system built using **NLP (TF-IDF)**, **FastAPI**, **Streamlit**, and the **TMDB API**.

## Features

- Search movies
- Movie recommendations using TF-IDF + Cosine Similarity
- Trending movies
- Popular movies
- Top Rated movies
- Upcoming movies
- Movie posters from TMDB
- FastAPI backend
- Streamlit frontend

## Tech Stack

- Python
- Pandas
- Scikit-Learn
- FastAPI
- Streamlit
- TMDB API

## Project Structure

```
app.py
main.py
movies_metadata.csv
df.pkl
tfidf.pkl
tfidf_matrix.pkl
indices.pkl
requirements.txt
README.md
```

## Installation

```bash
pip install -r requirements.txt
```

Run backend

```bash
python -m uvicorn main:app --reload
```

Run frontend

```bash
python -m streamlit run app.py
```

## Screenshots

(Add screenshots later)
