# 🎬 Movie Recommendation System

This project is a **content-based movie recommender system** built using Python. It recommends similar movies based on textual features such as genre, cast, crew, and keywords.

## 📌 Features

- Recommends 5 similar movies based on the selected movie
- Uses NLP techniques to process and vectorize movie data
- Implements cosine similarity to measure movie closeness
- Simple and efficient logic in a Jupyter Notebook

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn (`CountVectorizer`, `cosine_similarity`)
- NLTK (`PorterStemmer`)
- Jupyter Notebook

## 📂 Dataset

The dataset is assumed to be a cleaned and merged version of:
- `movies.csv`
- `credits.csv`
- Preprocessed into a `tags` column containing the combined text features

## 🛠 How it Works

1. Combine important features like title, genre, keywords, cast, and crew
2. Clean and normalize text data
3. Apply stemming and remove stopwords
4. Vectorize text using `CountVectorizer` (Bag of Words)
5. Compute pairwise cosine similarity between all movie vectors
6. Recommend top 5 similar movies for any selected input

## ▶️ Usage

1. Clone this repository or open the notebook:
