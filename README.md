# 🍷 Wine Quality Classification – Multiclass, Binary & Clustering Approaches

This repository presents an in-depth machine learning study focused on predicting wine quality (both red and white) using a variety of classification techniques. The project explores **native multiclass**, **One-vs-All**, **One-vs-One**, and **clustering-based** approaches for performance improvement and class reduction.

## 📂 Project Structure

All Python notebooks are located in the `Python Files` folder:

- `wine_bad_medium_good.ipynb`: Uses a clustering approach to group wine quality into three categories – bad, medium, and good.
- `wine_one_vs_all.ipynb`: Implements the One-vs-All strategy across several classifiers.
- `wine_one_vs_one.ipynb`: Implements the One-vs-One strategy, especially for natively binary classifiers.

Each notebook leverages popular libraries such as `scikit-learn`, `pandas`, `matplotlib`, `seaborn`, and `tensorflow`.

## 📘 Technical Report

The project is thoroughly documented in the accompanying PDF report:  
**`Wine_Quality_Classification_Models__Multiclass__Binary__and_Clustering_Approaches.pdf`**

This report is the **main reference** for understanding the study and includes:

- Exploratory Data Analysis (EDA)
- Preprocessing, normalization, and oversampling to handle class imbalance
- Performance evaluation using precision, recall, F1-score, and accuracy
- Comparative analysis across classification strategies
- Notes on data partitioning, experimental design, and limitations

> 📌 **Please read the report for a complete understanding of the implementation and findings.**

## 📊 Algorithms Used

All approaches were tested with the following models:

- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Neural Network

## 🧪 Evaluation

Each strategy was evaluated independently for **red** and **white** wine datasets using stratified splits for training, validation, and testing.

> A key insight: natively multiclass models (like Random Forest and Neural Networks with Softmax) consistently outperformed One-vs-All and One-vs-One adapted models.

## 📁 Dataset

Data was obtained from the UCI Machine Learning Repository:  
[https://archive.ics.uci.edu/ml/datasets/Wine+Quality](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

## 👤 Author

Developed by **Vinícius Franklin Pedroso Mansur de Azevedo**  
Juiz de Fora – April 2025
