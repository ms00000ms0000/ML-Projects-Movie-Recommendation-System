# 🎬 ML Project - Movie Recommendation System  

## 🚀 Overview  
This **Machine Learning project** is a **Movie Recommendation System** that suggests similar movies based on user input.  
The system utilizes **TF-IDF Vectorizer** for text feature extraction and **Cosine Similarity** to measure similarity between movies.  

Key attributes such as **Genres, Keywords, Tagline, Cast, and Director** are combined to form a meaningful representation of each movie.  
Using **difflib**, the system matches the user’s input with titles from the dataset and retrieves movies with the highest similarity scores.  

This project demonstrates how **content-based recommendation systems** function, providing **personalized movie suggestions** using **NLP and similarity-based algorithms** for an engaging user experience.  

---

## 🔍 About the Project  
The **Movie Recommendation System** is a **content-based filtering** model that recommends movies similar to a user-specified title.  
It leverages **Natural Language Processing (NLP)** techniques and **Cosine Similarity** to analyze movie metadata and compute closeness scores between films.  

This project showcases the foundation of modern **recommendation engines**, similar to those used by **Netflix, IMDb, and Amazon Prime Video**, emphasizing **user personalization** and **content relevance**.  

---

## 🧠 Model Architecture  
The recommendation process involves the following key steps:  

1. **Data Preprocessing** – Cleaning and merging textual features (Genres, Keywords, Tagline, Cast, Director).  
2. **Feature Extraction** – Using **TF-IDF Vectorizer** to convert text into numerical feature vectors.  
3. **Similarity Computation** – Applying **Cosine Similarity** to measure how closely movies relate to one another.  
4. **Recommendation Engine** – Using **difflib.get_close_matches()** to find the most relevant movie titles and return the top matches.  

---

## 🧾 Dataset Description  
The dataset contains detailed information about movies, including genres, cast, crew, and keywords.  

| Feature | Description |
|----------|-------------|
| **Title** | Name of the movie |
| **Genres** | Movie categories (e.g., Action, Comedy, Drama) |
| **Keywords** | Key themes or concepts related to the movie |
| **Tagline** | Short promotional line or slogan |
| **Cast** | Main actors involved |
| **Director** | Movie director |
| **Overview** | Short description or summary |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computations  
* **Pandas** – Data manipulation and cleaning  
* **Scikit-learn** – TF-IDF Vectorizer and Cosine Similarity  
* **Difflib** – String matching for user input  
* **Matplotlib / Seaborn** – Optional visualizations  

---

## 🚀 Features  
* Provides **personalized movie recommendations**  
* Uses **TF-IDF Vectorization** for text-based feature representation  
* Employs **Cosine Similarity** for comparing movie metadata  
* Utilizes **Difflib** for matching user-input titles  
* Demonstrates **content-based filtering** technique  
* Can easily be **extended** with collaborative or hybrid filtering methods  

---

## 📊 Results  
The system successfully recommends movies most similar to the input title with high accuracy and relevance.  
By combining **movie metadata** and **NLP-based similarity metrics**, it provides reliable and engaging movie suggestions.  

Example:  
> 🎥 *Input Movie:* “Inception”  
>  
> 🔎 *Top Recommendations:* Interstellar, The Prestige, The Dark Knight, Shutter Island, Memento  

---

## 📁 Repository Structure  

```
📦 ML-Projects-Movie-Recommendation-System
│
├── Movie_Recommendation_System.ipynb # Main Jupyter Notebook
├── movies.csv # Dataset containing movie metadata
├── requirements.txt # Required dependencies
└── README.md # Project documentation
```

---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Projects-Movie-Recommendation-System.git
   cd ML-Projects-Movie-Recommendation-System
   ```

2. **Install dependencies:**
    ```bash   
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
    ```bash
   jupyter notebook Movie_Recommendation_System.ipynb
   ```

4. **Enter any movie title in the input section to get top 5 similar movie recommendations.**

---

## 📈 Future Improvements

* Integrate collaborative filtering for user-based personalization

* Deploy the system as a Streamlit or Flask web app

* Include poster images and links for each recommended movie

* Extend to a hybrid recommendation engine combining content and user ratings

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
