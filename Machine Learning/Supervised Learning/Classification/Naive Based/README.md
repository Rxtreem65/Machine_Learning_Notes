# Concept of Probability
- Probability is likely hood of an event to occur. 
- It can be broadly classified as follows:
    - Marginal probability
    - Joint probability
    - Conditional probability
    
### 1. Marginal Probability
- It is the probability of all the favorble events upon the total events.
- It is denotes as follows: 
<img src="https://render.githubusercontent.com/render/math?math=P(A) = \frac{Event A occured}{All the outcomes}">

$$P(A) = \frac{Event A occured} {All the outcomes}$$

### 2. Conditional Probability
- It occurs when two dependent varibles or events are involved
- It is probability of ocurance of an event say **A** given that **B** has already occured, where A and B are dependent events.
- It can be denoted as follows:<img src="https://render.githubusercontent.com/render/math?math=P(\frac{A}{B})=\frac{P(\frac{B}{A})P(A)}{P(B)}">


### 3. Joint Probability
- It is probability of an event say **A** and **B** to ocuur simultaniously. 
- It can be denoted as follows:<img src="https://render.githubusercontent.com/render/math?math=P(A and B)">


# Bayes Theorem
- It provides method of calculating conditional probability without the joint probability.
- And as it calculates conditional probabilities, it projects the probability of an event A on that of another event B.
- Mathematically it states as follows: <img src="https://render.githubusercontent.com/render/math?math=P(\frac{A}{B}) = \frac{P(\frac{B}{A}) P(A)}{P(B)}">

**P(A/B):** Posterior probability
**P(A):** Prior probability
**P(B|A):** Likelihood
**P(B):** Evidence

Also, replacing the tearms in the above equation we get,

Posterior = Likelihood * Prior / Evidence


# Naive Bayes
- It is a classification algorithm beloging to supervised machine learning based on Bayes Theorem.
- Naive Bayes is has three types as follows:
    1. [Guassian Naive Bayes](https://github.com/Rxtreem65/Machine_Learning_Notes/blob/main/Machine%20Learning/Supervised%20Learning/Classification/Naive%20Based/Gaussian_naive_bayes.ipynb)
    2. [Bernouli Naive Bayes](https://github.com/Rxtreem65/Machine_Learning_Notes/blob/main/Machine%20Learning/Supervised%20Learning/Classification/Naive%20Based/Bernoulli_Naive_Bayes.ipynb)
    3. [Mutltinodal Naive Bayes]
    
- Uses:
    * It is very effective in text classification that contains training dataset of high dimensionality.
    * It is very helpful in building fast machine learning model and to get quick predictions.
    * use cases are: spam filteration, sentimental analysis, article classification.


### Why is it called Naive ?
- It is called naive because it assumes that the occurrence of a certain feature is independent of the occurrence of the other features.

### Steps to be followed to make 
1. convert the given dataset in two frequency table
2. Generate the likelihood table by finding the probability of given features
3. Now, a Bayes theorem is used to calculate the poster probability.

### Advantages of Naive Bayes
* it is one of the esiest and fastest model of classification 
* it can be used for both binary and multiclass classification
* it is most popular theorm for text classification

### Disadvantage
* It assumes that the features are independent from each other, which might not be always be the case when we deal with real life data.