# 🎬 Movie Recommender System

A **content-based movie recommendation system** that suggests similar movies based on user selection. The system uses movie metadata and similarity algorithms to generate accurate and relevant recommendations.

---

## 🚀 Features

- 🎥 Recommends movies similar to a selected title
- 🧠 Content-based filtering using cosine similarity
- 📊 Uses movie metadata (genres, keywords, cast, overview)
- ⚡ Fast and efficient recommendations
- 🧑‍💻 Simple and user-friendly interface (CLI / Web)

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Scikit-learn** – Similarity calculation
- **Streamlit** - Web application

---

## 📂 Project Structure
```
Movies_Recommender_System
│
├── app.py
├── model
├── requirements.txt
├── .gitignore
└── README.md
```
---

## ⚙️ How It Works

1. Movie features are combined into a single text representation  
2. Text is vectorized using **CountVectorizer**
3. **Cosine similarity** is calculated between movies
4. Top similar movies are recommended to the user

---

## 📥 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/AnjaliRayyy/Movies-Recommender-System.git
cd Movies-Recommender-System
```
### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the application
```bash
streamlit run main.py
```

---

## 📌 Example Use Case

- User selects a movie such as **"Inception"**
- The system analyzes its features and similarity with other movies
- The recommender suggests movies like:
  - Interstellar
  - The Prestige
  - Shutter Island
  - The Matrix

This helps users discover movies similar in theme and style.

---

## 📊 Dataset

- The system uses a **movie metadata dataset** (CSV format)
- Common attributes include:
  - Movie title
  - Genres
  - Keywords
  - Cast
  - Overview

The quality of recommendations depends on the richness of this data.

---

## ⚠️ Notes

- This is a **content-based recommendation system**
- It does **not** rely on user ratings or past user behavior
- Best suited for small to medium-sized datasets
- Recommendations are based purely on similarity, not popularity

---

## 🤝 Contributing

Contributions are welcome!  
If you have ideas for improvements or new features, feel free to:
- Fork the repository
- Create a new branch
- Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it.

---

## ⭐ Acknowledgements

- Inspired by recommendation system concepts
- Built using Python and machine learning libraries
- Dataset sourced from publicly available movie datasets
