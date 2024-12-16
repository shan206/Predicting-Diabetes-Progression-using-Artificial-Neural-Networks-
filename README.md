# Predicting-Diabetes-Progression-using-Artificial-Neural-Networks-
It seems you're asking about formatting a list of sections for documentation, and you want to add a "dot" in front of "Data" or perhaps use a bullet point list. Here's how it can look with dots (or bullet points)
# Project Overview
This project aims to predict the progression of diabetes in patients using Artificial Neural Networks (ANN). The model utilizes the well-known Diabetes dataset from the sklearn library to train and evaluate its performance. The goal is to provide healthcare professionals with insights into how different factors influence diabetes progression, aiding in better treatment plans and preventive measures.

# Table of Contents

- **Installation**
- **Usage**
- **● Data Description**
- **Model Architecture**
- **Results**
- **Visualizations**
- **Contributing**
- **License**
- 
# Installation
To run this project, you need to have Python 3.x installed along with the following packages:
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow keras keras-tuner
# Usage
1.Clone the repository:
git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction
2.Open the Jupyter Notebook:
jupyter notebook Diabetes_Prediction.ipynb
3.Run the cells in the notebook to execute the data preprocessing, model training, evaluation, and visualizations.
# Data Description
The dataset used in this project is the Diabetes dataset from sklearn. It contains various health metrics of patients, including:
- **Age**
- **sex**
- **Body Mass Index (BMI)**
- **Average Blood Pressure**
- **Six blood serum measurements (S1-S6)**
The target variable represents a quantitative measure of diabetes progression one year after baseline.
# Model Architecture
The model consists of:
- **An input layer that accepts features from the dataset.**
- **Multiple hidden layers with ReLU activation functions.**
- **An output layer that predicts the diabetes progression value.**
# Results
The performance of the model was evaluated using Mean Squared Error (MSE) and R² Score before and after potential improvements:

| **Metric**           | **Before Improvement** | **After Improvement** |
|-----------------------|------------------------|------------------------|
| **Mean Squared Error (MSE)** | 2811.82               | 2569.98               |
| **R² Score**          | 0.40                   | 0.51                  |  
# Visualizations
The project includes various visualizations to analyze:
- **Actual vs. Predicted values before and after model improvement.**
- **Loss curves for training and validation during model training.**
- **Relationships between features and the target variable.**
# Contributing
Contributions are welcome! If you have suggestions for improvements or additional features, please open an issue or submit a pull request.
# License
This project is licensed under the MIT License - see the LICENSE file for details.

