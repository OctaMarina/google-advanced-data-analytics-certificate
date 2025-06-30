# Logistic Regression

**Logistic regression** is a statistical model used to predict the probability of a binary outcome — for example, yes/no, 0/1, or success/failure.

Unlike linear regression, which predicts continuous numeric values, logistic regression predicts a probability between 0 and 1. If the probability is above a certain threshold (commonly 0.5), the model classifies the outcome as 1 (positive); otherwise, it classifies it as 0 (negative).

## When to Use It

- Spam detection (spam or not)
- Disease prediction (sick or healthy)
- Customer churn (leave or stay)
- Loan approval (approve or deny)

## The Sigmoid Function

The logistic model uses the **sigmoid function** to convert a linear combination of input variables into a probability:

<p>
  <strong>P(Y = 1)</strong> = 
  <span style="display: inline-block; vertical-align: middle;">
    1 / (1 + e<sup>−(β₀ + β₁X₁ + β₂X₂ + ... + βₙXₙ)</sup>)
  </span>
</p>

## Advantages

- Easy to implement and interpret
- Efficient for binary classification
- Works well with linearly separable data

## Limitations

- Assumes a linear relationship in the log-odds
- Can perform poorly on complex, non-linear problems

**Summary:**  
Logistic regression is a simple and powerful tool for binary classification tasks where outcomes are limited to two categories.
