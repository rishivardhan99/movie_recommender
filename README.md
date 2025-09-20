# 🎬 Movie Recommendation System

## 📌 Overview
This is a basic **collaborative filtering based movie recommender system** using Python, Pandas, and scikit-learn.  
It computes **cosine similarity** between users or items to recommend top movies.

---

## 📂 Project Structure
```
movie_recommender/
│── data/
│   └── ratings.csv        # dataset (MovieLens)
│── MovieRecommender.ipynb # Jupyter Notebook
│── requirements.txt       # dependencies
│── README.md              # project guide
```

---

## ⚙️ Requirements
- Python 3.8+
- Pandas
- Scikit-learn
- Jupyter Notebook

Install all requirements:
```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run
1. Download MovieLens dataset → place `ratings.csv` inside `data/` folder.
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook MovieRecommender.ipynb
   ```
3. Run all cells → see recommendations for a sample user.

---

## 📊 Example Output
- User-Item Matrix
- Cosine Similarity Matrix
- Top-N Movie Recommendations for a user
