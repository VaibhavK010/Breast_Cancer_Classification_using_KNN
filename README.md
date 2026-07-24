# Breast Cancer Classification using K-Nearest Neighbors (KNN)

## Student Details

- **Name:** Vaibhav Kumar
- **Registration Number:** 23BCE11814
- **Application Number:** IN26010758
- **Batch:** 2B
- **University:** VIT Bhopal University
- **Program:** B.Tech Computer Science and Engineering

---

## Objective

The objective of this assignment is to build a K-Nearest Neighbors (KNN) classification model to predict whether a breast tumor is Malignant (M) or Benign (B) based on diagnostic measurements. The project demonstrates data preprocessing, feature scaling, model training, prediction, and evaluation using multiple classification metrics.

---

## Dataset Link

Breast Cancer Wisconsin Diagnostic Dataset

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

---

## Libraries Used

- Pandas
- NumPy
- Scikit-learn

---

## Methodology

1. Load the dataset.
2. Perform exploratory data analysis.
3. Remove unnecessary columns.
4. Encode the diagnosis column.
5. Split the dataset into training and testing sets.
6. Standardize feature values using StandardScaler.
7. Train a KNN classifier with K = 5.
8. Predict test data.
9. Evaluate the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## Results

The KNN classifier achieved excellent classification performance with high Accuracy, Precision, Recall, and F1-Score. The confusion matrix indicated very few misclassifications, making the model suitable for breast cancer prediction.

---

## Conclusion

The KNN algorithm successfully classified breast tumors with excellent performance after feature scaling. Standardization significantly improved the effectiveness of distance calculations used by KNN. Although the algorithm provides high accuracy for this dataset, its prediction time increases with larger datasets because it computes distances from every training sample.

---

## Repository Structure

```
Assignment-4/
│── Assignment-4.ipynb
│── README.md
```

> **Note:** The dataset is **not included** in this repository. Please download it from the Kaggle link provided above.
