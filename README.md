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

<img width="2534" height="1290" alt="image" src="https://github.com/user-attachments/assets/130b4172-3c43-4f6e-974e-f16ceede6580" />
<img width="2516" height="1300" alt="image" src="https://github.com/user-attachments/assets/1e1f42b4-62fe-4a4a-b1d8-6762ecf0807c" />
<img width="2556" height="1284" alt="image" src="https://github.com/user-attachments/assets/e22c35ba-9cba-4096-9541-824fc507f483" />
<img width="2542" height="1324" alt="image" src="https://github.com/user-attachments/assets/414d6ebd-a22e-4ba1-a086-7802a9437224" />
<img width="2448" height="1290" alt="image" src="https://github.com/user-attachments/assets/7394b9ef-c093-4f85-9814-b6eb4aa805be" />
<img width="2450" height="1250" alt="image" src="https://github.com/user-attachments/assets/a12f608f-0648-446f-9f18-6c22943e83f0" />





