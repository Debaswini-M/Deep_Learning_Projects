# 🌸 Iris Flower Classification Using a Neural Network

This project demonstrates a classification model for the famous Iris flower dataset using a simple artificial neural network built with Keras. It trains a neural network to classify iris flowers into three species based on four features: sepal length, sepal width, petal length, and petal width.

---

## 📊 Dataset

The iris dataset is loaded from sklearn.datasets and contains 150 samples evenly divided among three classes:
- Setosa (class 0)
- Versicolor (class 1)
- Virginica (class 2)

Each sample contains 4 features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

---

## 🏗️Model Architecture

The neural network is implemented using Keras Sequential API with the following layers:
- Input layer with 4 input features
- Two hidden layers with 16 neurons each and ReLU activation
- Output layer with 3 neurons (one per class) and softmax activation

The model uses sparse categorical crossentropy as the loss function and Adam optimizer.

---


## 🏋️Training

- Train/test split: 80% train, 20% test
- Batch size: 16
- Number of epochs: 300
- Validation data: test set used for validation during training

During training, accuracy and loss metrics are recorded for both training and validation sets.

---


## 🚀Usage

- After training, the model is evaluated on the test set to display validation loss and accuracy.
- Predictions on new flower input data can be made using the model's `predict` method.
- The predicted flower species class is printed based on the highest predicted probability.

---


## 📈Visualization

- Accuracy and loss graphs for training and validation sets are plotted using matplotlib.
- A confusion matrix displays the performance of the model on the test set, showing correct and incorrect classifications for each class.

---


---


## 📋Requirements

- Python 3.x
- TensorFlow/Keras
- scikit-learn
- matplotlib
- numpy

---


## ⚙️How to Run

1. Clone the repository  
2. Install required libraries: `pip install tensorflow scikit-learn matplotlib numpy`  
3. Run the Python script to train the model and generate visualizations  
4. Use the model for prediction and evaluation as shown in the code  

---

This project provides a simple example of using a Multi-Layer Perceptron neural network to classify iris flowers, demonstrating essential steps of data loading, preprocessing, model training and evaluation, and visualization of results.

---

## 👩🏻‍💻Author

This project was created and maintained by **Debaswini-M**.

---


