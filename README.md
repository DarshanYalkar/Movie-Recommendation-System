# 🎬 Movie Recommendation System

## 📌 Overview

This project is a **Movie Recommendation System** that suggests movies based on user preferences using **content-based filtering**. It analyzes movie features like genres, keywords, tagline, cast, and director to recommend similar movies.

The system uses **TF-IDF Vectorization** and **Cosine Similarity** to find relationships between movies and provide accurate recommendations. 

---

## 🚀 Features

* Recommend movies based on user input
* Uses content-based filtering technique
* Handles misspelled movie names using `difflib`
* Displays top 30 similar movies
* Efficient and fast recommendation system

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity

---

## 📂 Dataset

* Dataset used: `movies.csv`
* Contains information like:

  * Movie title
  * Genres
  * Keywords
  * Tagline
  * Cast
  * Director

---

## ⚙️ Project Workflow

### 1. Import Libraries

* Load required libraries like NumPy, Pandas, and Scikit-learn

### 2. Data Collection & Preprocessing

* Load dataset using Pandas
* Select important features:

  * genres, keywords, tagline, cast, director 
* Handle missing values by replacing them with empty strings

### 3. Feature Engineering

* Combine selected features into a single column
* Convert text data into numerical vectors using **TF-IDF Vectorizer** 

### 4. Similarity Calculation

* Compute similarity using **Cosine Similarity**
* Measures similarity between two movie vectors

### 5. Recommendation System

* Take movie name as input
* Find closest match using `difflib`
* Get similarity scores
* Sort movies based on similarity
* Display top 30 recommended movies 

---

## 📊 How It Works

* Each movie is converted into a vector using TF-IDF
* Cosine similarity calculates similarity between vectors
* Movies with highest similarity scores are recommended

**Cosine Similarity Formula:**

```
Cosine Similarity = (A · B) / (||A|| × ||B||)
```

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

### 2. Navigate to Project Folder

```bash
cd movie-recommendation-system
```

### 3. Install Dependencies

```bash
pip install numpy pandas scikit-learn
```

### 4. Run the Project

* Open Jupyter Notebook or Python file
* Run all cells
* Enter your favourite movie name when prompted

---

## 💡 Example

```
Enter your favourite movie name: Avatar

Movies suggested for you:

1. Avatar: The Way of Water  
2. Guardians of the Galaxy  
3. Star Trek  
...
```

---

## 📈 Future Improvements

* Add web interface using Flask/Django
* Improve recommendation accuracy
* Deploy project on cloud
* Add user login system
* Use hybrid recommendation (collaborative + content-based)

---

## 📌 Conclusion

This project demonstrates how machine learning techniques like **TF-IDF and Cosine Similarity** can be used to build an efficient movie recommendation system that enhances user experience.

---

## 🙌 Author

**Darshan Yalkar**
