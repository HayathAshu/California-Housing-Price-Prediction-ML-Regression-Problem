# 🏡 California Housing Price Prediction  
Predicting median house values using Machine Learning (Regression Project)

---

## 🔶 Tech Stack  
![Python](https://img.shields.io/badge/Python-3.8+-orange?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML%20Library-orange?logo=scikitlearn)

---

## 📌 Project Overview  
This project focuses on predicting **California house prices** using multiple features such as:

- Median Income  
- Housing Median Age  
- Total Rooms / Total Bedrooms  
- Population & Households  
- Latitude & Longitude  

The dataset is sourced from Kaggle and is widely used for regression problems.

🎯 **Goal:** Build, train, and evaluate ML models to predict *median_house_value*.

---

## 📂 Dataset  
**Source:** Kaggle – *California Housing Prices Dataset*  
- https://www.kaggle.com/datasets/camnugent/california-housing-prices  

You can download it automatically using:

```python
import kagglehub

path = kagglehub.dataset_download("camnugent/california-housing-prices")
print("Path to dataset files:", path)
