# Machine Learning Tutorial – Decision Tree

## 📌 Project Overview

This project demonstrates a complete implementation of a **Decision Tree classifier** using Python.
It is designed as a step-by-step tutorial covering the full machine learning workflow, from data loading to model evaluation and improvement.

The project uses the **Bank Marketing Dataset** to predict whether a customer will subscribe to a bank product (binary classification problem).

---

## 📂 Project Structure

```
├── decision_tree.py              # Python script version
├── decision_tree.ipynb          # Google Colab / Jupyter Notebook version
├── tutorial.pdf                 # Detailed written tutorial
├── bank-full.csv                # Dataset file
└── README.md                    # Project documentation
```

---

## ⚙️ Requirements

Make sure you have Python installed (Python 3.8+ recommended).

Install required libraries using:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 How to Run the Project

### 🔹 Option 1: Run Python Script

1. Download or clone the repository
2. Open terminal in project folder
3. Run:

```
python decision_tree.py
```

---

### 🔹 Option 2: Run Notebook (Recommended for learning)

1. Open `decision_tree.ipynb`
2. Run all cells step-by-step

You can use:

* Jupyter Notebook
* Or upload to Google Colab

---

## 📊 What the Code Does

The project follows these steps:

1. **Load Dataset**
   Reads the Bank Marketing dataset

2. **Data Exploration**
   Understand structure using `.info()` and `.describe()`

3. **Data Preprocessing**

   * Convert target variable (yes/no → 1/0)
   * Encode categorical variables
   * Split features and target

4. **Train-Test Split**

   * 80% training
   * 20% testing

5. **Entropy Visualization**

   * Understand decision tree splitting logic

6. **Model Training**

   * Decision Tree Classifier (max_depth=5)

7. **Prediction**

   * Generate predictions on test data

8. **Evaluation**

   * Accuracy
   * Classification Report
   * Confusion Matrix

9. **Visualization**

   * Decision tree structure
   * Feature importance

10. **Model Improvement**

* Depth testing
* Overfitting analysis

11. **Example Prediction**

* Predict result for a single sample

---

## 📈 Output Examples

The code generates:

* Entropy curve
* Confusion matrix heatmap
* Decision tree diagram
* Feature importance graph
* Depth vs accuracy graph

---

## 📚 Dataset

* Source: UCI Machine Learning Repository
* Dataset: Bank Marketing

Link:
https://archive.ics.uci.edu/dataset/222/bank+marketing

---

## 🔗 Additional Resources

* Google Colab Notebook:
  (Add your Colab link here)

---

## 📖 Tutorial

A full step-by-step explanation is available in:

```
tutorial.pdf
```

---

## 🧠 Key Concepts Covered

* Classification
* Decision Trees
* Entropy & Information Gain
* Overfitting & Underfitting
* Model Evaluation Metrics

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Author

Developed as part of a Machine Learning coursework project.
