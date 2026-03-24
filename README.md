# 🎬 TMDB Movie Recommendation System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Processing-150458.svg)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-orange.svg)](https://scikit-learn.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-FF4B4B.svg)](https://streamlit.io/)

## 📖 Overview
The TMDB Movie Recommendation System is a personalized engine designed to suggest films based on user preferences and historical data. By processing large-scale movie datasets to extract and vectorize key features (genres, cast, crew, and plot overviews), this system applies cosine similarity algorithms to identify underlying patterns between films and generate highly accurate, content-based top-N recommendations. The entire model is wrapped in an intuitive Streamlit interface for real-time user interaction.

## ✨ Key Features
* **Content-Based Filtering:** Recommends movies similar to a user's selection by analyzing textual metadata (tags, overview, cast, director).
* **Text Vectorization:** Utilizes Scikit-Learn's `CountVectorizer` to convert textual data into mathematical vectors for similarity computation.
* **Dynamic Poster Fetching:** Integrates with the official TMDB API to dynamically fetch and display high-quality movie posters for every recommended film.
* **Interactive Web App:** A clean, responsive user interface built entirely in Python using Streamlit.

## 🛠️ Technology Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Cosine Similarity, Text Vectorization)
* **Frontend/Deployment:** Streamlit
* **External API:** TMDB (The Movie Database) API

## 🚀 Installation & Setup

**1. Clone the repository**
```bash
git clone [https://github.com/594ishaniverma/TMDB-Movie-Recommendation-System.git](https://github.com/594ishaniverma/TMDB-Movie-Recommendation-System.git)
cd TMDB-Movie-Recommendation-System