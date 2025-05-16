# Conditional probability


Is used in:
- Finance
- Insurance
- Science
- Machine learning
---
### Dependent events
Two events are dependent if the occurrence of one event affects the probability of the other event.
`P(A and B) = P(A) * P(B|A)`
where `P(B|A)` is the probability of event B given that event A has occurred.

`P(B|A) = P(A and B) / P(A)`

Example:
- Acceptance rate: 10 out of 100 applicants are accepted.(10%)
- Scholarships awarded: 2 out of 100 accepted students.(2%)

Probaility events:
- A: Student is accepted
- B: Student is awarded a scholarship

P(A and B) = P(A) * P(B|A)

P(A and B) = 10/100 * 2/100 = 1/500 = 0.2%

---
## Bayes theorem

P(A|B) = P(B|A) * P(A) / P(B)

-  <b>prior probability </b>: the probability of an event before new data is collected
-  <b>posterior probability</b>: the probability of an event after new data is collected

### Bayesian statistics 
A powerful method for analyzing and interpreting data in modern data analytics


* <b>P(A) = Prior probability
* <b>P(A|B) = Posterior probability

### Example:

You are planning an outdoor event and you want to have good weather

Probability calculation:
* Overall chance of rain = 10%
* All days start off cloudy = 40%
* Rainy days start of cloudy = 50%

Probabilities:
* <b>Prior probability</b> = the probability of a rainy day (10%)
* <b>Posterior probability</b> = the probability of a rainy day given that it is cloudy 

Event A = rain and Event B = cloudy
P(Rain|Cloudy) = P(Cloudy|Rain) * P(Rain) / P(Cloudy)

P(Rain)  = 10%
P(Cloudy) = 40%
P(Cloudy|Rain) = 50%

P(Rain|Cloudy) = 12.5%


### Explain of P(A|B)
We're sure that the event A is true, but we want to know the probability of event B given that A is true.

P(Cloud|Rain):
We're sure that is cloudy, but we want to know the probability of rain given that it is cloudy.

P(Rain|Cloud):
We're sure that it is rainy, but we want to know the probability of cloudy given that it is rainy.
---
## The expended version of Bayes theorem
P(A|B) = P(B|A) * P(A) / (P(B|A)*P(A) + P(B|not A)*P(not A))

### Example
- 1% of the population has the medical condition
- if a person has the condition, there's a 95% chance that the test is positive
- if a person does not have the condition, there's a 2% chance that the test is positive
- Given a person test positive what is the chance that they have the condition?

So let:
- A = the person has the condition
- B = the test is positive
- P(A) = 0.01
- P(B|A) = 0.95
- P(B|not A) = 0.02

P(A|B) = 0.95*0.01/(0.95*0.01+0.02*0.99) = 0.32.4%