# Concept of Probability
- Probability is likely hood of an event to occur. 
- It can be broadly classified as follows:
    - Marginal probability
    - Joint probability
    - Conditional probability
    
### 1. Marginal Probability
- It is the probability of all the favorble events upon the total events.
- It is denotes as follows: 
$$P(A) = \frac{Event A occured} {All the outcomes}$$

### 2. Conditional Probability
- It occurs when two dependent varibles or events are involved
- It is probability of ocurance of an event say **A** given that **B** has already occured, where A and B are dependent events.
- It can be denoted as follows: 
<img src="https://latex.codecogs.com/svg.latex?\Large&space;P(frac{A}{B}) = \frac{P(\frac{B}{A}) P(A)}{P(B)}" title="P(frac{A}{B}) = \frac{P(\frac{B}{A}) P(A)}{P(B)}" />


$$P(frac{A}{B}) = \frac{P(\frac{B}{A}) P(A)}{P(B)}$$









# Bayes Theorem
It projects the probability of an event A on that of another event B.

Naive bayes algorithm:
<img src="https://latex.codecogs.com/svg.latex?\Large&space;P(frac{A}{B}) = \frac{P(\frac{B}{A}) P(A)}{P(B)}" title="P(frac{A}{B}) = \frac{P(\frac{B}{A}) P(A)}{P(B)}" />

$$P(frac{A}{B}) = \frac{P(\frac{B}{A}) P(A)}{P(B)}$$

It is a classification algorithm beloging to supervised machine learning based on Bayes Theorem.

Uses:
* It is very effective in text classification that contains training dataset of high dimensionality.
* It is very helpful in building fast machine learning model and to get quick predictions.
* use cases are: spam filteration, sentimental analysis, article classification.

# Naive Bayes
**Why is it called Naive ?**
It is called naive because it assumes that the occurrence of a certain feature is independent of the occurrence of the other features.

