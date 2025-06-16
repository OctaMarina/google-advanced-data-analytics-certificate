# Construct confidence interval for a proportion

## Steps for constructing a confidence interval:
1. Identify a sample statistic
2. Choose a confidence level: ex. 95%
3. Find the margin of error: z-score * SE where SE is standard error
4. Calculate the interval: 

Upper limit = Sample statistic + margin of error

Lower limit = Sample statistic - margin of error

=><b>[Upper Limit, Lower Limit]</b>


### Z-SCORE
A **Z-score** is a statistical measure indicating how many standard deviations an observation is from the mean of a dataset.

- **Positive Z-score**: value above the mean.
- **Negative Z-score**: value below the mean.
- **Z-score = 0**: value equal to the mean.

**Formula**:
<p>
  <i>Z</i> = 
  <span style="display:inline-block; vertical-align:middle;">
    <sup><i>x</i> − <i>μ</i></sup>&frasl;<sub><i>σ</i></sub>
  </span>
</p>

- <strong><i>x</i></strong> = observed value
- <strong><i>μ</i></strong> = mean
- <strong><i>σ</i></strong> = standard deviation

| Confidence level | Z-score |
|------------------|---------|
| 90%              | 1.645   |
| 95%              | 1.96    |
| 99%              | 2.58    |

This table shows common confidence levels and their corresponding Z-scores. The confidence level indicates how sure you are that your calculated interval includes the true population parameter. The Z-score is the standard deviation value used to construct confidence intervals at these specific confidence levels.

---
## Construct a confidence interval
Example:

<b>Battery Life</b>

* Sample mean = 20.5 hrs
* Sample standard deviation = 1.7 hrs
* Population standard deviation


<h3>Standard Error (SE) Formula:</h3>

<p>
  SE = 
  <span style="display: inline-block; vertical-align: middle;">
    <sup>σ</sup>&frasl;<sub>√n</sub>
  </span>
</p>

<ul>
  <li><strong>σ</strong> = standard deviation of population is known, otherwise standard deviation of the sample</li>
  <li><strong>n</strong> = sample size</li>
</ul>

1. Identify a sample statistics: mean
2. Confidence level: 95%
3. Find the margin of error: z-score * SE = 1.96 * 0.15
4. Calculate the interval: [20:12 hours, 20:48 hours]