# Movie_Recommendation_System

A content-based Movie Recommendation System built using Python and Machine Learning techniques. The system analyzes movie information such as genres, keywords, plot descriptions, cast members, and directors to recommend movies that are similar to a movie selected by the user.

## 📌 Project Summary

The Movie Recommendation System is designed to help users discover movies based on their interests.
It uses Natural Language Processing (NLP) techniques and content-based filtering to analyze movie characteristics and calculate similarities between movies.
The project uses the TMDB 5000 Movies and Credits datasets. Movie information is processed, transformed into numerical vectors, and compared using Cosine Similarity.
When a user enters a movie title, the system identifies the selected movie and returns the five most similar movies based on their content.

## ✨ What It Does

- Accepts a movie title as input.
- Analyzes movie descriptions, genres, keywords, cast, and directors.
- Processes textual information using NLP techniques.
- Converts movie information into numerical representations.
- Calculates similarities between movies.
- Recommends the five most similar movies.
- Allows users to discover movies with similar themes, genres, and other characteristics.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Dataset loading, manipulation, and preprocessing |
| NumPy | Numerical operations |
| Scikit-learn | Text vectorization and similarity calculations |
| NLTK | Text processing and stemming |
| Jupyter Notebook | Development and experimentation |
| TMDB Dataset | Movie information and credits |

## 📂 Dataset

The project uses two datasets from the TMDB 5000 Movie Dataset:

**1. tmdb_5000_movies.csv**

Contains movie information, including:
- Movie ID
- Title
- Overview
- Genres
- Keywords
- Popularity
- Release information

**2. tmdb_5000_credits.csv**

Contains movie credit information, including:
- Movie title
- Cast members
- Characters
- Crew members
- Directors

The two datasets are merged using the movie title to combine movie information with its credits.

### How the Recommendation Model Works

**1 – Feature Extraction**
**2 – Text Representation**
**3 – Vectorization**
**4 – Similarity Calculation**
**5 – Movie Recommendation**

### Example Recommendation

Input:

```python
recommend ("Iron Man 3")
```

Example output:

```text
Iron Man
Iron Man 2
Avengers: Age of Ultron
Captain America: Civil War
X-Men
```

**Note:** This is a recommendation system rather than a traditional classification or regression model. It does not predict movie ratings or box-office performance. this project is purely for academic purposes.
Dataset: TMDB 5000 Movie Dataset.

The dataset is used for educational and machine learning experimentation.
