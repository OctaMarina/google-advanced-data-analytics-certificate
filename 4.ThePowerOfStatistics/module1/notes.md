# Module 1

## What is A/B Testing?
- A method to compare two versions of something (e.g., emails, ads).
- Goal: Find which version performs better.
- Common in digital marketing (email campaigns, website banners, online ads).

## Key Steps:
1. Define the goal (conversion rate, click rate, etc.).
2. Choose the control (A) and variation (B).
3. Decide on sample size.
4. Run the test on a random sample of users.
5. Analyze results for statistical significance.

## Sample
- A subset of the population used for testing or analysis.
- Must be representative to ensure valid conclusions.

## Confidence Interval
- A range of values that is likely to contain the true population parameter.
- Example: 95% confidence interval means we are 95% sure the true value lies within that range.

## Descriptive Statistics
- Used to **summarize and describe** the main features of a dataset.
- Focuses on central tendency, dispersion, and distribution.

### Examples:
- Mean (average)
- Median (middle value)
- Mode (most frequent value)
- Standard deviation (spread of data)
- Range (difference between max and min)

## Inferential Statistics
- Used to **make predictions or generalizations** about a population based on a sample.
- Helps draw conclusions beyond the data observed.

### Key concepts:
- Hypothesis testing
- Confidence intervals
- p-values
- Regression analysis

## Representative Sample
- A sample that accurately reflects the characteristics of the overall population.
- Ensures that conclusions drawn from the sample can be generalized.

## Measure of dispersion
- Values that represent the spread of a dataset

## Measures of central tendency:
- **Mean**: The average; sum of all values divided by the number of values.
- **Median**: The middle value in an ordered dataset.
    - If the number of values is **odd**, the median is the **middle value**.
    - If the number of values is **even**, the median is the **average of the two middle values**.

- **Mode**: The value that appears most frequently in the dataset.

When to use median or mean?
If there are outliers use median, else use mean

### Detecting Outliers (using Mean and Median)
- If the **mean** is much higher or lower than the **median**, it may indicate outliers.
- Outliers pull the **mean** in their direction, while the **median** stays more stable.

## Measures of dispersion
- Range: The difference between the largest and smallest value in a dataset
- Variation: The average of the squared difference of each data point from the mean.
## Sample Standard Deviation
- Measures how much values in a **sample** deviate from the **mean**.
- Expressed in the same units as the data.

### Formula:
s = sqrt[ (1 / (n - 1)) * Σ(xᵢ - x̄)² ]
where n is the number of observation in the sample
- It is the **square root** of the **sample variance**.
- Uses **n - 1** (not n) to correct for bias when working with a sample — known as **Bessel's correction**.

### Interpretation:
- Small standard deviation → values are close to the mean.
- Large standard deviation → values are spread out.


## What to look in a new dataset?
- Measures of central tendency(mean, median)
- Measures of dispersion(spread)