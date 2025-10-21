# 🏠 House Price Prediction using ANN

This project implements an **Artificial Neural Network (ANN)** to predict whether a house’s price is above or below the median value using structured housing data.  
The dataset used comes from the Kaggle repository: [House Price Data](https://www.kaggle.com/datasets/moewie94/housepricedata).

---

## 📘 Overview

The goal of this project is to demonstrate how an ANN can be built from scratch using **TensorFlow** and **Keras** for classification tasks on real-world housing data.  
It includes data preprocessing, model training, evaluation, testing, and visualization.

---

---

## 🏗️ Dataset Information

The dataset contains information about house attributes, including area, average number of rooms, age, and population density.  
The **target variable** represents whether a house’s price is above or below the median price.

**Key Features:**
- `AvgAreaIncome`: Average income of residents in the area  
- `AvgAreaHouseAge`: Average age of houses in the area  
- `AvgAreaNumberofRooms`: Average number of rooms per house  
- `AreaPopulation`: Population in the area  
- `Price`: Price of the house (target)

**Target:** Binary classification (Above Median = 1, Below Median = 0)

---

## 🧠 Technologies Used

- Python 3.10+
- Keras
- NumPy, Pandas
- Matplotlib
- Scikit-learn

---

## ⚙️ Workflow
1. **Load Data:** Import data and inspect using Pandas.  
2. **Preprocess Data:** Handle missing values, normalize features, and encode target labels.  
3. **Split Dataset:** Create training and testing sets.  
4. **Build Model:** Define the ANN architecture using Keras.  
5. **Train and Validate:** Optimize weights using Backpropagation.  
6. **Evaluate Model:** Use accuracy, loss, and confusion matrix.

---
## 🪪 License

This project is licensed under the **MIT License** — feel free to use and modify it with proper attribution.

---
## 👨‍💻 Author

🌐 [Debaswini-M](https://github.com/Debaswini-M)

---
