# 🎬 Machine Learning Approaches for Movie Rating Prediction on IMDb Dataset

This project explores and compares various machine learning models to predict IMDb movie ratings using a combination of movie metadata and user review statistics. The goal is to analyze which features influence ratings the most and to build accurate predictive models.

---

## 📁 Project Structure

├── Code/
│ ├── data_description.ipynb
│ └── preprocessing and model training.ipynb
├── Dataset/
│ ├── IMDb movies.csv
│ └── IMDb ratings.csv
├── README.md

---

## 🧠 Models Used

- Linear Regression (with binned output)
- Random Forest Regressor
- Gradient Boosting Regressor

Ratings were binned into categories for better classification visualization using confusion matrices.

---

## 📊 Key Insights

- Features like `duration`, `votes`, and `average vote` are important predictors.
- Gradient Boosting performed the best in terms of accuracy and generalization.
- Proper preprocessing (handling missing data, scaling, encoding) significantly improved results.

---

## 📌 Data Source

IMDb dataset from Kaggle:  
https://www.kaggle.com/datasets/stefanoleone992/imdb-extensive-dataset

---

## ⚙️ Tech Stack

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🚀 How to Run

1. Clone the repo:
  git clone https://github.com/Abkas/Machine-Learning-Approaches-for-Movie-Rating-Prediction-on-IMDb-Dataset.git


2. Open the notebooks:
  cd Machine-Learning-Approaches-for-Movie-Rating-Prediction-on-IMDb-Dataset
  jupyter notebook
---

## 👨‍💻 Author

**Abhishek Magar**  

