# 🤖 Machine Learning Final Project – Football Match Prediction & Home Sale Clustering

This project was created for my **Machine Learning course (CCS2213)** at Albukhary International University. It focuses on applying machine learning to solve **two real-world problems**:

1. **Predicting the outcome of football matches** using historical data (Supervised Learning).
2. **Grouping homes by similar characteristics** using housing data (Unsupervised Learning).

---

## 📌 Project Goals

1. Use machine learning to **predict** whether a football match will result in a win, loss, or draw.
2. Use clustering to **find hidden patterns** in home sale data (e.g., grouping homes by price, size, or location).
3. Compare the performance of different ML models using accuracy and visualization tools.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `football match.ipynb` | Jupyter Notebook for predicting football match outcomes. |
| `football match data.csv` | The dataset used for football prediction. |
| `home sell.ipynb` | Jupyter Notebook for clustering home sale data. |
| `Home Sale Data.csv` | The dataset used for home sale clustering. |
| `README.md` | This documentation file. |

---

## ⚽ Football Match Prediction (Supervised Learning)

### What I Did:
- Used past football match data (like team stats and results).
- Applied four machine learning models:
  - **K-Nearest Neighbors (KNN)**
  - **Support Vector Machine (SVM)**
  - **Logistic Regression**
  - **Decision Tree**

### Result:
- **SVM** and **Logistic Regression** gave the most accurate predictions.
- These models can help fans, analysts, or betting systems make better guesses about upcoming matches.

---

## 🏠 Home Sale Clustering (Unsupervised Learning)

### What I Did:
- Used data about homes (like price, location, and size).
- Grouped similar homes into clusters using:
  - **KMeans Clustering**
  - **Hierarchical Clustering**
- Evaluated cluster quality using **Silhouette Score**.

### Result:
- KMeans created **3 distinct clusters** with a silhouette score of **0.45**.
- Helps real estate agents or buyers understand different categories of homes.

---

## 🛠️ Tools & Libraries

- **Languages**: Python
- **Libraries**: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `numpy`
- **Platform**: Jupyter Notebook

---

## 📊 Key Takeaways

- **Supervised learning** is useful when you have labeled data and want to make predictions.
- **Unsupervised learning** is great for discovering patterns in data without labels.
- Choosing the right algorithm matters: each has its strengths depending on the data.

---

## 🎓 Course Information

- **Course**: Machine Learning (CCS2213)
- **Lecturer**: Prof. Dr. Zurinahni binti Zainol
- **Student**: Abdullah Al Hadi (AIU21102089)

---

## 🔗 References

- Football match dataset: [Kaggle](https://www.kaggle.com/code/saife245/football-match-prediction)
- Home sale dataset: [Kaggle](https://www.kaggle.com/datasets/emrahaydemr/home-sales-data-details-in-istanbul)

---

## 📜 License

This project is for **educational purposes** only.
