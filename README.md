# IMDB Rating Prediction Using Machine Learning

![IMDB Prediction](https://img.shields.io/badge/Machine%20Learning-IMDB%20Prediction-blue)

## 📌 Project Overview

This project aims to predict IMDB ratings of movies using various machine learning models. The dataset used in this study was sourced from Kaggle and includes features such as **genre, budget, director, cast, and release year**. The problem is formulated as a **regression task**, and several models were evaluated, with **XGBoost Regressor** achieving the best performance.

## 🚀 Features

- **Data Preprocessing & Feature Engineering**
  - Handling missing values
  - Encoding categorical features
  - Log transformation for skewed data
- **Machine Learning Models Evaluated**
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - K-Nearest Neighbors (KNN)
  - XGBoost Regressor (Best performing)
- **Performance Metrics**
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

## 📂 Dataset

The dataset used in this project is titled **"IMDB Score Prediction for Movies"**, available on Kaggle. It consists of various movie-related features:

- **Input Features:** Color, Director Name, Genre, Budget, Cast, Release Year, Facebook Likes, User Reviews, etc.
- **Target Variable:** `imdb_score` (Movie rating on a scale of 0 to 10)

## 📊 Model Performance

| Model           | RMSE (Train) | RMSE (Test) | R² (Train) | R² (Test) | Accuracy  |
|---------------|--------------|-------------|------------|-----------|-----------|
| Linear Regression | 0.119 | 0.120 | 0.411 | 0.387 | 95.43% |
| Decision Tree     | 0.029 | 0.049 | 0.716 | 0.148 | 97.0%  |
| Random Forest    | 0.014 | 0.035 | 0.925 | 0.565 | 97.74%  |
| KNN              | 0.040 | 0.049 | 0.443 | 0.159 | 96.74%  |
| Lasso Regression | 0.044 | 0.043 | 0.351 | 0.346 | 97.15%  |
| Ridge Regression | 0.044 | 0.043 | 0.351 | 0.346 | 97.15%  |
| **XGBoost**      | **0.004** | **0.033** | **0.991** | **0.611** | **97.86%** |

## 🛠 Installation & Usage

### 🔧 Requirements
- Python 3.8+
- `numpy`
- `pandas`
- `scikit-learn`
- `xgboost`
- `matplotlib`
- `seaborn`

---

## 🎯 Future Improvements  
Here are some potential improvements for this project:  

- 🔍 **Incorporating NLP Techniques**: Analyzing movie reviews to enhance prediction accuracy.  
- 📊 **Using Deep Learning**: Implementing neural networks to capture complex relationships in the data.  
- 📈 **Expanding Feature Set**: Adding social media metrics, box-office earnings, and critic scores.  

---

## 🤝 Contributing  
Contributions are welcome! If you’d like to improve this project:  

1. **Fork** the repository.  
2. **Create** a new branch (`git checkout -b feature-branch`).  
3. **Commit** your changes (`git commit -m "Add new feature"`).  
4. **Push** to the branch (`git push origin feature-branch`).  
5. **Open a Pull Request**.  

---

## 📜 References  
1. **Sharda & Delen (2006)** - Predicting box-office success with neural networks.  
2. **Choudhury & Gaonkar (2018)** - Machine learning approaches to predicting movie success.  
3. **Breiman (2001)** - Random Forest: An ensemble learning technique.  
4. **Goodfellow et al. (2016)** - Deep Learning, MIT Press.  
5. **Chen & Guestrin (2016)** - XGBoost: A scalable tree boosting system.  

---

## 📬 Contact  
For any questions or suggestions, feel free to reach out:  

📩 Email: 777eerol.exe@gmail.com

---

## 📄 License  
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.  