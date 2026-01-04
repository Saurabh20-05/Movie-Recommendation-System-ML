# 🎬 Movie Recommendation System using Content-Based Filtering

This project uses **Content-Based Recommendation** techniques to suggest movies similar to a user’s favorite movie.  
It analyzes movie metadata such as **genres, keywords, tagline, cast, and director** using **TF-IDF Vectorization** and **Cosine Similarity** to generate accurate and relevant recommendations.

---

## 📘 Project Overview

- This is a **Content-Based Movie Recommendation System**
- It recommends movies based on **textual similarity of movie features**
- The system compares movies using **TF-IDF + Cosine Similarity**
- Designed to provide **personalized movie suggestions** without user ratings

---

## 🗂️ Dataset Information

- **Dataset Name:** Movies Dataset  
- **Source:** CSV file (`movies.csv`)  
- **Format:** Text + Categorical Data  
- **Type:** Movie metadata dataset  

---

## 📌 Dataset Description

- Each row represents a **movie**
- Important features used:
  - **Genres**
  - **Keywords**
  - **Tagline**
  - **Cast**
  - **Director**
- These features are combined to form a single text representation for each movie

---

## 🧠 Technologies Used

- **Python 3.x**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Difflib**

---

## ⚙️ Project Workflow

1. Import required Python libraries
2. Load the movies dataset using Pandas
3. Select important movie features
4. Handle missing values by replacing them with empty strings
5. Combine selected features into a single text column
6. Convert text data into numerical vectors using **TF-IDF Vectorizer**
7. Compute **Cosine Similarity** between movie vectors
8. Accept user input for a favorite movie
9. Find the closest matching movie name
10. Recommend top similar movies based on similarity score

---

## 🔍 Recommendation Logic

- **TF-IDF Vectorization** converts movie descriptions into numerical vectors
- **Cosine Similarity** measures similarity between movies
- Movies with the **highest similarity scores** are recommended
- **Difflib** is used to handle spelling mistakes in movie names

---

## 🧪 Sample Input

Enter your favourite movie name: Iron Man

Movies suggested for you based on 'Iron Man':

1. Iron Man 2
2. Avengers: Age of Ultron
3. Captain America: Civil War
4. The Avengers
5. Avengers: Infinity War
...

---

## 👨‍💻 Author

**Developed by Saurabh**

Feel free to connect, explore, or contribute to this project!

---

⭐ If you found this project helpful, don’t forget to **star the repository**!
