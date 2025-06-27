# 🎬 Movie Recommendation System (NLP-Based)

This is a movie recommendation model that works using NLP and vectorization of tokens.

It basically converts things like **genre**, **language**, **ratings**, and **overview** into **tokens** (words). Then it takes the average of those tokens to create a single vector that represents each movie.

After that, it compares the vector of the movie you watched with the rest of the dataset using **cosine similarity**, and gives you similar movies to watch next.

---

## 🧠 What the Model Does

- Takes movie metadata (overview, genre, language, ratings)
- Tokenizes that data (splits it into words)
- Converts each token into a vector using **Word2Vec**
- Averages all vectors to get one vector per movie
- Compares vectors using **cosine similarity**
- Returns top recommended movies

---

## 🔧 Model Used

- **Word2Vec** from `gensim`

---

## 📚 Libraries I Used

- `pandas`
- `numpy`
- `gensim`


---

## 🧪 How to Use

1. Enter a movie you have watched.
2. The model finds its vector.
3. It compares that with all other movies.
4. You get top similar movies recommended.

---



---

## 📌 Notes

I built this project using **Google Colab** with help from **ChatGPT**, and I learned a lot about how Word2Vec works, tokenizing text, and comparing vectors using cosine similarity. This is part of my journey into NLP and machine learning.
