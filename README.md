# Cancer Prediction Model
<br>
This project involves building a Breast Cancer Prediction Model using Logistic Regression to classify tumors as malignant (cancerous) or benign (non-cancerous) based on features derived from fine needle aspirates of breast masses. The dataset contains 30 numerical features, including radius, texture, perimeter, area, and shape-related characteristics of cell nuclei. It consists of 569 samples, with 357 benign and 212 malignant cases, and has no missing values. Logistic regression is used for its effectiveness in binary classification tasks. The model aims to assist in early cancer diagnosis by accurately predicting tumor types, which can help healthcare professionals make timely and informed decisions.
<br><br>

### Dataset Overview: <br>
Source: The dataset originates from digitized images of breast mass fine needle aspirates (FNA), publicly available on the UCI Machine Learning Repository and other sources.

#### Attributes:

- **ID Number:** Unique identifier for each sample.
- **Diagnosis (Target Variable):** Binary classification—M for malignant and B for benign.
- **30 Features:** Derived from the characteristics of cell nuclei, including:
  - **Radius:** Average distance from the center to the perimeter.
  - **Texture:** Variation in grayscale intensity.
  - **Perimeter, Area:** Geometric properties of nuclei.
  - **Smoothness, Compactness, Concavity, Symmetry:** Shape-related features.
  - **Fractal Dimension:** Complexity of cell boundaries.
- Each feature has three variations—mean, standard error, and worst-case value—resulting in 30 numerical features.

#### Data Source: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
