# 🎬 IMDB Movie Recommendation System Using Storylines

## 📌 Project Overview
This project implements a **content-based movie recommendation system** using IMDb movie storylines.  
The system analyzes movie plot summaries using **Natural Language Processing (NLP)** techniques and recommends similar movies based on textual similarity.

By leveraging **TF-IDF vectorization** and **Cosine Similarity**, the application suggests the **top 5 most relevant movies** for a user-provided storyline.  
The project also includes a **Streamlit-based interactive web interface** for real-time recommendations.

---

## 🎯 Problem Statement
With the increasing volume of movie content, users often struggle to find movies aligned with their interests.  
This project aims to automatically recommend movies based on storyline similarity by analyzing textual data instead of user ratings or reviews.

---

## 🧠 Business Use Cases
- **Movie Recommendation Systems**  
  Suggest movies based on story preferences rather than ratings.

- **Entertainment Platforms**  
  Provide personalized content discovery experiences.

- **Content-Based Filtering**  
  Recommend similar movies even for new or unrated titles.

- **User Engagement Enhancement**  
  Improve user retention by offering relevant suggestions.

---

## 🛠️ Tech Stack
### Programming Language
- Python

### Libraries & Tools
- Pandas
- NumPy
- Scikit-learn
- NLTK / Regex (Text Cleaning)
- Selenium (for data scraping – conceptual)
- Streamlit

### NLP & ML Techniques
- Text Cleaning & Tokenization
- TF-IDF Vectorization
- Cosine Similarity
- Content-Based Recommendation

---

## 📂 Project Structure
IMDB-Storyline-Recommender/
│
├── imdb_2024_storylines.csv
├── imdb_recommender.ipynb
├── app.py
├── README.md

yaml
Copy code

---

## 🔄 Project Workflow

### 1. Data Collection
- Movie names and storylines scraped from IMDb (conceptually using Selenium).
- Data stored in CSV format for further processing.

### 2. Data Preprocessing
- Converted text to lowercase
- Removed punctuation and special characters
- Cleaned storyline text for NLP processing

### 3. Text Vectorization
- Applied **TF-IDF Vectorizer** to convert storylines into numerical vectors.
- Removed stop words to focus on meaningful terms.

### 4. Similarity Calculation
- Computed **Cosine Similarity** between movie storylines.
- Ranked movies based on similarity scores.

### 5. Recommendation Engine
- User inputs a storyline
- System returns the **Top 5 most similar movies**
- Similarity scores used for ranking relevance

### 6. Streamlit Deployment
- Interactive UI to accept user input
- Displays recommended movies and their storylines
- Designed for real-time interaction

---

## 📊 Evaluation Metrics
- **Cosine Similarity Score** – Measures textual similarity
- **Ranking Accuracy** – Relevance of top recommended movies
- **User Interpretability** – Clear explanation of recommendations

---

## 📈 Results & Insights
- TF-IDF effectively captures key storyline themes.
- Cosine similarity provides accurate content-based recommendations.
- The system performs well without relying on user ratings.
- NLP-based recommendation is lightweight and scalable.

---

## ⚠️ Note on Dataset
For evaluation purposes, the system is designed with a fallback mechanism that generates a sample dataset if the IMDb dataset is unavailable.  
This ensures reproducibility and uninterrupted execution during assessment.

---

## 🚀 How to Run the Project
1. Clone the repository
2. Open the Jupyter Notebook and run all cells  
   **OR**
3. Run the Streamlit app:
streamlit run app.py

yaml
Copy code
4. Enter a movie storyline to receive recommendations

---

## 🎯 Conclusion
This project demonstrates the practical application of NLP techniques in building a content-based recommendation system.  
By combining TF-IDF, cosine similarity, and an interactive UI, the solution provides meaningful and scalable movie recommendations suitable for real-world entertainment platforms.

---

## 👤 Author
**Manimaran Arockiyadoss**  
Data Analytics & Machine Learning Enthusiast
