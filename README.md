# 📘 Supervised Learning Algorithms: KNN & Decision Tree

Welcome to this repository showcasing two fundamental **Supervised Learning** techniques:

🔹 **K-Nearest Neighbors (KNN)**  
🔹 **Decision Tree Classifier**  

These models are implemented using **Python** and **Jupyter Notebooks** to provide clear visual and code-based understanding.

---

## 🧠 What is Supervised Learning?

Supervised learning is a type of machine learning where a model is trained on **labeled datasets** — meaning each data point has an input (features) and an output (target/label). The model learns to map inputs to outputs and can then make predictions on new, unseen data.

---

## 📊 Algorithms Overview

### 🔵 K-Nearest Neighbors (KNN)

**K-Nearest Neighbors (KNN)** is a simple yet powerful algorithm used for both classification and regression. It is **non-parametric**, meaning it makes no assumptions about the underlying data distribution.

#### 🔍 How it Works:
1. Store all training data points.
2. To classify a new data point:
   - Calculate its distance (e.g., Euclidean) to all other points in the training set.
   - Select the **K nearest neighbors** (data points with the smallest distances).
   - Assign the most common label among those neighbors as the prediction.

#### ✅ Key Features:
- Lazy learning (no training phase)
- Sensitive to the choice of **K**
- Performance can be improved using feature scaling and dimensionality reduction

---

### 🌳 Decision Tree Classifier

A **Decision Tree** is a supervised learning algorithm that is intuitive and interpretable. It works by breaking down the dataset into smaller and smaller subsets while simultaneously developing a tree structure.

#### 🔍 How it Works:
1. Starts at the **root node** with the full dataset.
2. Selects the best **feature** and **threshold** to split the data (using measures like **Gini Impurity** or **Entropy**).
3. Recursively splits data at each node until:
   - The node is pure (all data points belong to the same class), or
   - A maximum depth is reached.

#### ✅ Key Features:
- Easy to visualize and interpret
- Handles both numerical and categorical data
- Can easily overfit (often used with pruning or ensemble methods like Random Forest)

---

## 📂 Repository Structure

```bash
├── KNN_algorithm.ipynb           # Step-by-step implementation of KNN
├── Decisiontree_algorithm.ipynb  # Step-by-step implementation of Decision Tree
└── README.md                     # Project documentation
