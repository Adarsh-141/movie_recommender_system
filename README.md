# 🎬 Movie Advisor – Content-Based Recommendation System

## Overview

This project is a **Content-Based Movie Recommendation System** built using Python and Jupyter Notebook. It provides personalized movie suggestions based on similarities between movie features such as genres, keywords, taglines, cast, and crew.

The core idea is to recommend movies that are similar in content to a user's selected movie by analyzing textual data.

---

## Features

- 📌 **Content-Based Filtering** using movie metadata (title, cast, crew, genres, keywords, overview, tagline).
- 🧮 **Natural Language Processing (NLP)** for textual feature engineering.
- 🧠 **Cosine Similarity** used to compute movie similarities.
- 🔍 **Efficient Search** that allows users to find top recommendations quickly.
- 📊 Clean and interpretable notebook with step-by-step explanation.

---

## Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn)
- **Jupyter Notebook**
- **NLTK / Text preprocessing**
- **Cosine Similarity** (Scikit-learn)

---

## How It Works

1. **Data Preprocessing**  
   Load and clean movie metadata (genres, keywords, cast, etc.) from CSV files.

2. **Feature Extraction**  
   Combine relevant text fields into a single "soup" for vectorization.

3. **Vectorization**  
   Use `CountVectorizer` to convert text into a matrix of token counts.

4. **Similarity Scoring**  
   Compute cosine similarity scores between all movies based on their vector representations.

5. **Recommendation Engine**  
   Retrieve the top N movies similar to a user-specified movie.
   
