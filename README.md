#Task 10
# KNN – Handwritten Digit Classification

## 📌 Task Overview
This project demonstrates **handwritten digit classification** using the **K-Nearest Neighbors (KNN)** algorithm.  
The task focuses on understanding **distance-based classification**, the importance of **feature scaling**, and **K-value tuning**.

The **Sklearn Digits dataset** is used, which contains grayscale images of handwritten digits (0–9).

---

## 🛠 Tools & Technologies
- Python
- Scikit-learn
- Matplotlib
- NumPy

---

## 📊 Dataset
- **Dataset Name:** Sklearn Digits
- **Source:** `sklearn.datasets.load_digits()`
- **Total Samples:** 1797
- **Image Size:** 8 × 8 pixels
- **Features:** 64
- **Classes:** Digits (0–9)

---

## 🚀 Project Workflow

1. Load the digits dataset and verify data shape
2. Visualize sample digit images with labels
3. Split data into training and testing sets
4. Apply **StandardScaler** for feature scaling
5. Train KNN classifier with `K = 3`
6. Evaluate model accuracy
7. Test multiple K values (3, 5, 7, 9)
8. Plot **Accuracy vs K**
9. Generate **Confusion Matrix**
10. Display test images with predicted labels

---

## 📈 Model Evaluation

### Accuracy for Different K Values
| K Value | Accuracy |
|-------|----------|
| 3     | ~97–99%  |
| 5     | ~97–99%  |
| 7     | ~96–98%  |
| 9     | ~95–97%  |

*(Exact accuracy may vary due to random split)*

---

## 📉 Accuracy vs K Plot
A line graph is used to visualize how accuracy changes with different K values, helping to select the optimal K.

---

## 🧩 Confusion Matrix
The confusion matrix highlights:
- Correct classifications
- Misclassified digits
- Class-wise performance

---

## 🖼 Sample Predictions
The final output includes:
- 5 test digit images
- Corresponding predicted labels

This confirms that the trained model works correctly on unseen data.

---

## ❓ Interview Concepts Covered
- What is K in KNN?
- Why feature scaling is required in KNN
- Euclidean distance
- Effect of small vs large K
- Limitations of KNN

---

## 📁 Repository Contents
- `knn_digits_classification.ipynb` – Complete implementation
- `README.md` – Project documentation
- Plots and visual outputs (inside notebook)

---

## ✅ Conclusion
This project demonstrates a clear understanding of:
- Distance-based classification
- Feature scaling
- Hyperparameter tuning in KNN

The model achieves **high accuracy** on handwritten digit recognition and meets all task requirements.

---
