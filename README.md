# 📉 Principal Component Analysis (PCA) for Dimensionality Reduction

Demonstrating dimensionality reduction using **Principal Component Analysis (PCA)** to transform high-dimensional data into a lower-dimensional feature space while preserving the maximum possible variance.

![Python](https://img.shields.io/badge/Python-blue)
![Pandas](https://img.shields.io/badge/Pandas-150458)
![NumPy](https://img.shields.io/badge/NumPy-013243)
![Matplotlib](https://img.shields.io/badge/Matplotlib-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Unsupervised-success)
![Dimensionality Reduction](https://img.shields.io/badge/Dimensionality%20Reduction-PCA-blueviolet)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📖 Project Overview

This project demonstrates the application of **Principal Component Analysis (PCA)**, one of the most widely used dimensionality reduction techniques in machine learning.

The notebook follows a complete workflow beginning with synthetic data generation, feature scaling, and Principal Component Analysis before visualising the transformed dataset in a lower-dimensional feature space.

The primary objective of this project is to understand how PCA reduces the dimensionality of a dataset while preserving as much of the original information (variance) as possible.

Reducing dimensionality can simplify datasets, improve computational efficiency, reduce redundancy between features, and make high-dimensional data easier to visualise and interpret.

---

# 🎯 Problem Statement

Real-world datasets often contain many numerical features, making them difficult to visualise, analyse, and process efficiently.

The objective of this project is to demonstrate how **Principal Component Analysis (PCA)** transforms high-dimensional data into a smaller number of principal components while retaining the maximum possible variance within the data.

The project also illustrates the importance of feature scaling before applying PCA and visualises the transformed observations using the first two principal components.

---

# 📊 Dataset

This project does **not** use an external CSV dataset.

Instead, a synthetic dataset is generated programmatically using Scikit-learn:

```python
from sklearn.datasets import make_blobs

X, y = make_blobs(...)
```

The generated dataset contains multiple numerical features and distinct clusters, making it suitable for demonstrating dimensionality reduction using Principal Component Analysis.

### Dataset Summary

- Dataset Type: Synthetic Dataset
- Data Generation Library: Scikit-learn
- Data Generation Function: `make_blobs()`
- Feature Type: Numerical
- Learning Type: Unsupervised Learning
- Dimensionality Reduction Technique: Principal Component Analysis (PCA)

---

# 🛠️ Technologies Used

- 🐍 Python
- 📓 Jupyter Notebook
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 📈 Seaborn
- 🤖 Scikit-learn
- 📉 Principal Component Analysis (PCA)
- 📏 StandardScaler
- 💻 Visual Studio Code
- 🌐 Git
- 📂 GitHub

---

# ⚙️ Machine Learning Workflow

This project follows a structured workflow to demonstrate dimensionality reduction using Principal Component Analysis (PCA).

1. Import Required Libraries
2. Generate a Synthetic Dataset
3. Explore the Generated Dataset
4. Standardise Features using StandardScaler
5. Apply Principal Component Analysis (PCA)
6. Transform the Dataset into Principal Components
7. Create a DataFrame of Principal Components
8. Visualise the Reduced-Dimensional Data

---

# 📊 Data Generation

Instead of using a real-world dataset, this project generates a synthetic dataset using Scikit-learn's `make_blobs()` function.

The generated dataset contains multiple numerical features and distinct clusters, making it suitable for demonstrating how PCA transforms high-dimensional data into a lower-dimensional feature space.

The dataset is generated programmatically, ensuring that the project is fully reproducible without requiring an external CSV file.

---

# 🔍 Data Exploration

After generating the dataset, the observations are explored to understand the structure of the data before applying dimensionality reduction.

The notebook displays the generated feature values, allowing inspection of the dataset prior to preprocessing.

---

# 🧹 Feature Scaling

Before applying Principal Component Analysis, the numerical features are standardised using **StandardScaler**.

Feature scaling is an essential preprocessing step because PCA is sensitive to differences in feature scales. Standardisation ensures that each feature contributes equally when calculating the principal components.

The scaled dataset is displayed after preprocessing to verify that the transformation has been applied successfully.

---

# 📉 Principal Component Analysis (PCA)

Principal Component Analysis (PCA) is then applied to the standardised dataset.

The PCA model reduces the original feature space into **two principal components**, allowing the dataset to be represented in a lower-dimensional space while preserving as much of the original variance as possible.

This transformation simplifies the dataset, making it easier to visualise and analyse.

---

# 📋 Principal Component DataFrame

The transformed principal components are converted into a Pandas DataFrame.

The original cluster labels are then appended to the DataFrame, enabling the reduced-dimensional data to be visualised according to their corresponding groups.

---

# 📈 Data Visualisation

The transformed dataset is visualised using a scatter plot.

The plot displays the first principal component against the second principal component, with observations coloured according to their original cluster labels.

This visualisation demonstrates how PCA projects high-dimensional observations into a two-dimensional space while preserving the overall structure of the data.

The graphical representation provides an intuitive understanding of how dimensionality reduction can simplify complex datasets without losing significant information.

---

# 📊 Results

Principal Component Analysis (PCA) was successfully applied to a standardised synthetic dataset generated using Scikit-learn.

The workflow demonstrated how high-dimensional data can be transformed into a lower-dimensional representation while preserving the most significant variation within the dataset.

Key observations from the project include:

- The original dataset was successfully standardised before applying PCA.
- PCA transformed the dataset into **two principal components**.
- The transformed dataset was converted into a Pandas DataFrame for further analysis and visualisation.
- A scatter plot of the first two principal components was created to visualise the reduced-dimensional feature space.
- The visualisation demonstrated that PCA can effectively project high-dimensional observations into two dimensions while preserving the underlying structure of the data.

The project highlights how dimensionality reduction simplifies data visualisation and serves as an important preprocessing technique for many machine learning workflows.

---

# 💡 Skills Demonstrated

Throughout this project, the following machine learning and data analysis skills were applied:

- Unsupervised Machine Learning
- Dimensionality Reduction
- Principal Component Analysis (PCA)
- Synthetic Data Generation
- Data Exploration
- Feature Scaling
- StandardScaler
- Data Transformation
- Data Visualisation
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Understanding the concept of dimensionality reduction.
- Applying Principal Component Analysis (PCA) using Scikit-learn.
- Generating synthetic datasets with `make_blobs()`.
- Standardising numerical features before dimensionality reduction.
- Transforming high-dimensional data into principal components.
- Creating DataFrames from transformed data for further analysis.
- Visualising reduced-dimensional datasets using scatter plots.
- Understanding how PCA preserves the maximum possible variance while reducing the number of features.
- Building a complete unsupervised machine learning workflow using Python and Scikit-learn.

---

# 🚀 Future Improvements

Potential enhancements include:

- Calculate and visualise the explained variance ratio for each principal component.
- Compare PCA with other dimensionality reduction techniques such as t-SNE and UMAP.
- Apply PCA to real-world datasets with higher-dimensional feature spaces.
- Evaluate the impact of PCA on supervised machine learning model performance.
- Create interactive visualisations using Plotly.
- Build a Streamlit application to demonstrate PCA on user-uploaded datasets.

---

# 📂 Repository Structure

```text
pca-dimensionality-reduction/
│
├── pca_dimensionality_reduction.ipynb
├── pca_dimensionality_reduction.py
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 👤 Author

**Rushikesh Temghare**

MSc Data Science & Artificial Intelligence  
Bournemouth University

---

# 📄 License

This project is licensed under the **MIT License**.
