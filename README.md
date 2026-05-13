# 🎬 Movie Recommender System Using Machine Learning

## 📌 Overview

This project is a Machine Learning-based Movie Recommender System built using Python and Streamlit. The application recommends movies similar to a user's selected movie using content-based filtering and cosine similarity.

The system analyzes movie-related features and suggests movies with similar characteristics to improve user experience and personalized recommendations.

---

## 🚀 Features

* Movie recommendation based on user interest
* Content-based recommendation system
* Interactive Streamlit web application
* Fast and user-friendly interface
* Similar movie suggestions using cosine similarity

---

## 🧠 Recommendation System Types

### 1. Content-Based Filtering

Content-based systems recommend movies based on movie attributes and similarities. If a user likes a particular movie, the system recommends movies with related features.

### 2. Collaborative Filtering

Collaborative filtering recommends items based on similarities between users and their preferences.

### 3. Hybrid Recommendation System

Hybrid systems combine both content-based and collaborative filtering approaches for better recommendations.

---

## ⚙️ Technologies Used

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-102230?style=for-the-badge&logo=tensorflow&logoColor=orange" />
  <img src="https://img.shields.io/badge/Pickle-00599C?style=for-the-badge" />
</p>

---

## 📊 Machine Learning Concept Used

### Cosine Similarity

Cosine similarity is used to measure similarity between movie vectors.

* Value ranges from 0 to 1
* 0 → Completely different movies
* 1 → Highly similar movies

This helps in finding movies with similar content and recommending them to users.

---

## 📁 Project Structure

```bash
Movie-Recommender-System/
│
├── app.py
├── movie_list.pkl
├── similarity.pkl
├── requirements.txt
├── movie_recommender.ipynb
└── README.md
```

---

## ▶️ How to Run the Project

### Step 1: Clone Repository

```bash
git clone https://github.com/sakshi96078/Movie-Recommender-System.git
```

### Step 2: Create Virtual Environment

```bash
python -m venv myenv
```

### Step 3: Activate Environment

```bash
myenv\Scripts\activate
```

### Step 4: Install Requirements

```bash
pip install -r requirements.txt
```

### Step 5: Run Application

```bash
streamlit run app.py
```

---

## 🖼️ Application Preview

<img width="1161" height="836" alt="398554136-99a37b30-d562-418e-9cbd-fd70361fc1ae" src="https://github.com/user-attachments/assets/b839ab7e-8560-44dc-b794-527a973e6ff1" />


---

## 📂 Dataset

The project uses movie metadata and similarity matrices for generating recommendations.


---

⭐ If you found this project useful, consider giving it a star.
