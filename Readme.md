# 🌸 Iris Classification – Machine Learning Benchmark

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OMariam-SalemO/iris-classification-benchmark/blob/main/iris_classification_benchmark.ipynb)

## 📌 Project Overview

This project implements a Multi-Class Classification Pipeline using the Iris dataset.

The main objective is to train, evaluate, and compare two Machine Learning classification algorithms and analyze their performance using different evaluation metrics.

## 🎯 Project Objectives

- Explore and understand the Iris dataset.
- Perform Exploratory Data Analysis (EDA).
- Apply data preprocessing and feature scaling.
- Split the dataset into training and testing sets.
- Train multiple classification models.
- Evaluate model performance using classification metrics.
- Compare the performance of different models.
- Visualize decision boundaries.

## 📊 Dataset

The Iris dataset contains 150 samples belonging to three different species:

- Setosa
- Versicolor
- Virginica

**Features:**

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset is balanced, with 50 samples for each species.

## ⚙️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔬 Project Workflow

The project follows these steps:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Class Distribution Analysis
4. Feature Visualization using Pairplot
5. Feature and Target Separation
6. Train-Test Split (80/20)
7. Feature Scaling using StandardScaler
8. Model Training
9. Model Predictions
10. Model Evaluation
11. Confusion Matrix Visualization
12. Model Performance Comparison
13. Decision Boundary Visualization

## 🤖 Machine Learning Models

Two classification algorithms were implemented:

### 1. Logistic Regression

A supervised classification algorithm used to predict the probability of a sample belonging to different classes.

### 2. Decision Tree Classifier

A tree-based classification algorithm that makes predictions using a sequence of feature-based decisions.

## 📈 Model Evaluation

Both models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

Macro averaging was used for Precision, Recall, and F1-Score.

## 🏆 Model Comparison & Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 93.33% | 93.33% | 93.33% | 93.33% |
| Decision Tree | 93.33% | 93.33% | 93.33% | 93.33% |

**Results:**

- Both models achieved 93.33% accuracy.
- Both models achieved the same Macro F1-Score.
- Both models correctly classified 28 out of 30 test samples.
- Neither model outperformed the other on the current test set.

## 📉 Visualizations

The notebook includes several visualizations:

- Iris Class Distribution
- Feature Pairplot
- Logistic Regression Confusion Matrix
- Decision Tree Confusion Matrix
- Model Performance Comparison
- Logistic Regression Decision Boundary
- Decision Tree Decision Boundary

**Note:** Decision boundary visualizations use two features (Petal Length and Petal Width) for 2D visualization, while the benchmark models use all four features.

## 🚀 How to Run

You can run this project using Google Colab or locally on your machine.

### Option 1: Google Colab (Recommended)

1. Open the notebook file: `iris_classification_benchmark.ipynb`.
2. Click the **Open in Colab** button at the top of this README.
3. Sign in to your Google account if required.
4. Click **Runtime → Run all**.
5. Wait for all cells to execute and explore the results.

### Option 2: Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/OMariam-SalemO/iris-classification-benchmark.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Open the notebook using Jupyter Notebook or JupyterLab.
4. Run all cells.

## 📁 Repository Structure

```text
iris-classification-benchmark/
│
├── iris_classification_benchmark.ipynb
└── README.md
```

## 👩‍💻 Author

**Mariam Salem**

Machine Learning | Data Analysis | Data Science

---

⭐ If you find this project useful, feel free to star the repository!
