# Diabetes Classification Using Machine Learning

**Course:** Pattern Recognition and Machine Learning

This project presents a comparative study of several machine learning classification methods for diabetes prediction using the **Pima Indians Diabetes Dataset**.

## Project Overview

The goal of this project is to compare the performance of different classification algorithms and evaluate their ability to predict diabetes based on medical measurements.

The following methods were implemented and evaluated:

- Gaussian Naive Bayes
- Quadratic Discriminant Analysis (QDA)
- k-Nearest Neighbors (kNN)
- Distance-Weighted kNN
- Feature-Weighted kNN

Feature weights in the Feature-Weighted kNN model were computed using Pearson correlation coefficients calculated on the training data.

---

## Dataset

- **Dataset:** Pima Indians Diabetes Dataset
- **Number of samples:** 768
- **Number of features:** 8
- **Classification:** Binary (Diabetes / No Diabetes)

Main features include:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

---

## Repository Structure

```
├── Diabetes.ipynb              # Complete implementation
├── Diabetes_Report.pdf         # Full project report
├── Presentation.pdf            # Project presentation
├── README.md

```

---

## Results

The best overall performance was achieved by the **Feature-Weighted kNN** classifier.

| Method | Accuracy | Recall | F1-score |
|---------|---------:|--------:|----------:|
| Gaussian Naive Bayes | 76.47% | 69.09% | 67.86% |
| QDA | 79.08% | 69.09% | 70.37% |
| kNN | 83.66% | 70.91% | 75.73% |
| Distance-Weighted kNN | 84.31% | 76.36% | 77.78% |
| **Feature-Weighted kNN** | **84.31%** | **81.82%** | **78.95%** |

---

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (only for dataset splitting, preprocessing, and evaluation)

---

## Authors

- Dorina Keringer
- Dragana Maksimović

Faculty of Sciences  
University of Novi Sad
