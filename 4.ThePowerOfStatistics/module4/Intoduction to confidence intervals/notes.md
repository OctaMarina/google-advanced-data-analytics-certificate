# Introduction to confidence intervals

## Confidence intervals describe the uncertainty of an estimate for:
* The average return on investment for a stock portofolio
* The average maintenance costs for factory machinery
* The percentage of customers who will register for a rewards program
* The percentage of website visitors who will click on an ad


## Introduction to confidence intervals
<b>A point estimate uses a single values to estimate a population parameter. In contrast an interval estimate uses a range of values</b>


### Confidence interval:
* Sample statistic
* Margin of error
* Confidence level

### Margin of error
The maximum expected difference between a population parameter and a sample estimate

Example:
mean = 30

margin_of_error = +-2

So the interval will be [28,32]

### Confidence level
Describes the likelihood that a particular sampling method will produce a confidence interval that includes the population parameter

The confidence level does not mean there is a 95% probability that the actual parameter is within the calculated interval 
(the real parameter either is or is not within the interval). Rather, it reflects that, if the same estimation procedure is
repeated multiple times, 95% of the intervals produced would contain the true parameter.

If you have 95% confidence level you can expect:
1. 95% of intervals capture the population mean
2. 5% of intervals do not capture the population mean

### Common confidence levels:
* 90%
* 95%(popular)
* 99%

---
## Interpret confidence intervals

### Correct interpretation
Earlier, you learned that the confidence level expresses the uncertainty of the estimation process. Let’s discuss what 95% confidence means from a more technical perspective.

Technically, 95% confidence means that if you take repeated random samples from a population, and construct a confidence interval for each sample using the same method, you can expect that 95% of these intervals will capture the population mean. You can also expect that 5% of the total will not capture the population mean.

The confidence level refers to the long-term success rate of the method, or the estimation process based on random sampling.

For the purpose of our example, let’s imagine that the mean weight of all 10,000 penguins is 31 pounds, although you wouldn’t know this unless you actually weighed every penguin. So, you take a sample of the population.

Imagine you take 20 random samples of 100 penguins each from the penguin population, and calculate a 95% confidence interval for each sample. You can expect that approximately 19 of the 20 intervals, or 95% of the total, will contain the actual population mean weight of 31 pounds. One such interval will be the range of values between 28 pounds and 32 pounds. 

In practice, data professionals usually select one random sample and generate one confidence interval, which may or may not contain the actual population mean. This is because repeated random sampling is often difficult, expensive, and time-consuming. Confidence intervals give data professionals a way to quantify the uncertainty due to random sampling.

### Incorrect interpretations

One incorrect statement that is often made about a confidence interval at a 95% level of confidence is that there is a 95% probability that the population mean falls within the constructed interval.

In our example, this would mean that there’s a 95% chance that the mean weight of the penguin population falls in the interval between 28 pounds and 32 pounds.

This is incorrect. The population mean is a constant.

Like any population parameter, the population mean is a constant, not a random variable. While the value of the sample mean varies from sample to sample, the value of the population mean does not change. The probability that a constant falls within any given range of values is always 0% or 100%.  It either falls within the range of values, or it doesn’t.

For example, any given random sample of 100 penguins may have a different mean weight: 32.8 pounds, 27.3 pounds, 29.6 pounds, and so on. You can use a sampling distribution to assign a specific probability to each of your sample means because these are random variables. However, the population mean weight is considered a constant. In our example, if you weigh all 10,000 penguins, you’ll find that the population mean is 31 pounds. This value is fixed, and does not vary from sample to sample.