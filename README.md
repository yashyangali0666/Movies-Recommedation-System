# Movie Recommendation System

A Machine Learning based Movie Recommendation System that suggests similar movies based on user interests and movie content. This project uses content-based filtering techniques to recommend movies by analyzing features such as genres, keywords, cast, crew, and movie overview.

## Features

* Recommend movies similar to selected movies
* Content-based recommendation algorithm
* Interactive web interface using Streamlit
* Fast similarity search using cosine similarity
* Clean and user-friendly UI

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

## Dataset

TMDB 5000 Movies Dataset

## How It Works

The system processes movie metadata and creates tags by combining important features like genres, cast, crew, keywords, and overview. After text preprocessing, vectorization techniques are applied to calculate similarity between movies. Based on similarity scores, the system recommends top matching movies.

## Installation

```bash
pip install -r requirements.txt
```

## Run Project

```bash
streamlit run app.py
```

## Future Improvements

* Add collaborative filtering
* User login and watch history
* Movie posters and trailers
* Hybrid recommendation system
* Deploy on cloud platform

## Author

Yash Yangali
