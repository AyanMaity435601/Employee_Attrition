# Employee Attrition


We handled the imbalanced data by using some techniques like SMOTE, ADASYN, Tomek Links, SMOTETomek etc.

Here we used several machine learning classification model to see whether an employee will leave his/her job or not.
In the '.ipynb' file I have evaluated a brief exploratory data analysis on this dataset and then developed various machine learning models. 

##### we have read out some papers to do this project... Papers are given in the 'papers' folder... Further we have to tune our model to get good results on this data



## Model × Imbalance Technique — Accuracy Comparison

Train / Val / Test accuracy for all 5 models across 8 conditions. Best val accuracy per group is marked with ✅.

### No Balancing

| Model | Train | Val | Test | 
|---|---|---|---|
| Logistic Regression | 89.5% | 87.6% | 87.1% |
| Decision Tree | 88.2% | 86.4% | 82.3% |
| Random Forest | 86.9% | 85.7% | 83.7% |
| Gradient Boosting | 92.6% | 87.9% | 87.1% |
| SVM | 89.7% | **89.8% ✅** | 86.4% |

### SMOTE

| Model | Train | Val | Test | 
|---|---|---|---|
| Logistic Regression | 79.8% | 78.5% | 75.5% |
| Decision Tree | 93.1% | 82.6% | 78.2% |
| Random Forest | 94.1% | **89.1% ✅** | 86.4% | 
| Gradient Boosting | 96.2% | 86.0% | 85.0% |
| SVM | 90.7% | 84.2% | 78.2% |

### Random Oversampling

| Model | Train | Val | Test | 
|---|---|---|---|
| Logistic Regression | 77.5% | 78.1% | 72.1% |
| Decision Tree | 92.8% | 84.2% | 80.3% |
| Random Forest | 98.2% | **86.8% ✅** | 84.4% |
| Gradient Boosting | 94.4% | 84.9% | 77.6% |
| SVM | 99.7% | 84.5% | 78.9% |

### ADASYN

| Model | Train | Val | Test |
|---|---|---|---|
| Logistic Regression | 79.5% | 78.1% | 73.5% |
| Decision Tree | 90.1% | 81.1% | 79.6% | 
| Random Forest | 96.9% | **88.7% ✅** | 86.4% |
| Gradient Boosting | 97.2% | 86.4% | 85.0% |
| SVM | 97.4% | 85.3% | 80.3% |

### Tomek Links

| Model | Train | Val | Test | 
|---|---|---|---|
| Logistic Regression | 89.6% | 88.7% | 83.0% |
| Decision Tree | 90.8% | 84.5% | 83.7% |
| Random Forest | 86.9% | 85.7% | 83.7% |
| Gradient Boosting | 94.2% | 87.9% | 85.7% |
| SVM | 86.6% | **90.2% ✅** | 85.0% |

### Random Undersampling

| Model | Train | Val | Test | 
|---|---|---|---|
| Logistic Regression | 50.0% | **83.8% ✅** | 83.7% |
| Decision Tree | 76.5% | 73.6% | 70.8% | 
| Random Forest | 86.2% | 74.0% | 69.4% | 
| Gradient Boosting | 97.1% | 70.9% | 66.0% | 
| SVM | 70.0% | 83.4% | 81.6% |

### NearMiss

| Model | Train | Val | Test |
|---|---|---|---|
| Logistic Regression | 50.0% | **83.8% ✅** | 83.7% | 
| Decision Tree | 79.1% | 67.2% | 57.1% |
| Random Forest | 85.3% | 58.9% | 54.4% |
| Gradient Boosting | 97.7% | 59.6% | 59.2% |
| SVM | 62.1% | 80.0% | 74.8% |

### SMOTETomek

| Model | Train | Val | Test |
|---|---|---|---|
| Logistic Regression | 80.1% | 78.9% | 75.5% | 
| Decision Tree | 90.4% | 80.0% | 76.2% | 
| Random Forest | 96.8% | **89.1% ✅** | 86.4% |
| Gradient Boosting | 96.7% | 86.4% | 83.7% | 
| SVM | 90.7% | 84.2% | 78.9% |

---

## Conclusion

Among all the models and imbalance-handling techniques evaluated, **Random Forest with SMOTE** performs the best, achieving a validation accuracy of **89.1%** and a test accuracy of **86.4%**.

---



# Contributors

- [Ayan Maity](https://github.com/AyanMaity435601)
- [Debanjan Nanda](https://github.com/DebanjanNanda)




