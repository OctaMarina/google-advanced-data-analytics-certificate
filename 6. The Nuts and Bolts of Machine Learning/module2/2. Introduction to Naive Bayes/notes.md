# Introduction to Naive Bayes
## Naive Bayes
A supervised classification technique that is based on Bayes' Theorem with an assumption of independence among predictors
### Key Assumptions
- **Class-conditional independence**: Each feature is assumed to be independent of the others.
- **Equal importance of features**: All predictors are assumed to contribute equally.
### Advantages
- Easy to implement and interpret
- Fast training and low computational cost
- Scalable to large datasets
- Works well in tasks like **spam detection** and **text classification**

### Limitations
- Real data rarely meets independence assumptions
- **Zero-frequency problem**: When a class-feature combo doesn't occur, leading to zero probability (handled via smoothing)



## Posterior probability 
The probability of an event occurring after taking into consideration new information

---
# PACE in machine learning: The construct and execute stages
## Key evaluation metrics for classification models


### 1. Accuracy
**What it measures:**  
The overall proportion of correct predictions.

**Formula:**  
`Accuracy = (TP + TN) / (TP + TN + FP + FN)`

- **TP** = True Positive  
- **TN** = True Negative  
- **FP** = False Positive  
- **FN** = False Negative

**Best used when:** Classes are balanced (e.g., 50/50 split).

-

### 2. Precision
**What it measures:**  
Out of all predicted positive cases, how many were actually correct?

**Formula:**  
`Precision = TP / (TP + FP)`

**Best used when:** False positives are costly (e.g., spam detection).



### 3. Recall (Sensitivity)
**What it measures:**  
Out of all actual positive cases, how many were correctly predicted?

**Formula:**  
`Recall = TP / (TP + FN)`

**Best used when:** False negatives are costly (e.g., disease detection).



### 4. F1 Score
**What it measures:**  
The harmonic mean of precision and recall. A balance between the two.

**Formula:**  
`F1 Score = 2 * (Precision * Recall) / (Precision + Recall)`

**Best used when:** You need a single performance score and the data is imbalanced.



### Quick Summary Table

| Metric     | What it Measures                        | When to Use                                |
|------------|------------------------------------------|---------------------------------------------|
| Accuracy   | Overall correctness                      | Balanced classes                            |
| Precision  | Correct positives vs. predicted positives | When false positives are costly             |
| Recall     | Correct positives vs. actual positives   | When false negatives are costly             |
| F1 Score   | Balance between precision and recall     | When data is imbalanced or a trade-off is needed |


### Precision-Recall (PR) Curve
**What it shows:**  
The trade-off between **precision** and **recall** at different classification thresholds.

- **X-axis:** Recall  
- **Y-axis:** Precision  
- Useful when dealing with **imbalanced datasets** (e.g., fraud detection).

**Key Insight:** A higher curve means better performance.



### ROC (Receiver Operating Characteristic) Curve
**What it shows:**  
The trade-off between the **True Positive Rate (Recall)** and the **False Positive Rate**.

- **X-axis:** False Positive Rate (FPR = FP / (FP + TN))  
- **Y-axis:** True Positive Rate (TPR = Recall)  
- Useful for understanding how well a model distinguishes between classes.

**Key Insight:** The closer the curve is to the top-left, the better.



### AUC (Area Under the Curve)
**What it means:**  
A single number summarizing the ROC or PR curve.

- **AUC-ROC:** Measures overall model performance  
  - 1.0 = perfect classifier  
  - 0.5 = random guessing  
- **AUC-PR:** Especially informative with imbalanced data

**Key Insight:** Higher AUC = better model at separating classes.