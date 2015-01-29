{:title "Statistics Notes"
 :layout :post
 :tags  ["mth", "statistics"]
 }


    mean   μ = ∑x/n
    median (n+1)/2 on ordered sequence
    mode   most frequent
    
    variance  = ∑(x-μ)2/n = ∑x2/n - μ2
    std-dev = σ = √(variance)
    
    standard score   z = x - μ / σ
 [way of comparing values across different data sets ie diff means y std dev's
  transforms sets of data into new theretical distn with mean of and std dev of 1
  standard score = # of std devs from the mean ]

## Probability
defn: **Event** is any occurence that has a probability attached to it.

    probability P(A) = n(A)/ n(S)
     n(A)= number of ways of getting an event A
     n(S) = number of possible outcomes
    S known as Probability Space or sample Space
    A' is known as complemntary event of A (ie A does NOT occur)
    P(A') = 1 - P(A)

    intersection ∩ (and)
    union        ∪ (or)
    "given"  |

    P(A | B) = probability of event A 'given' event B
    P(A | B) = P(A ∩ B)/ P(B)

### Law of Total Probability
     P(B) = P(B ∩ A) + P(B ∩ A')
        = P(A)P(B | A) + P(A')P(B | A')
The Law of Total probability is the denominator of Bayes' Theorem

### Bayes Theorem 
    P(A | B) = p(A) x P(B | A)/(P(A) x P(B | A) + P(A') x P(B | A') )

    Independent events P(A | B) = P(A)

## Discrete Probability Distributions
A random variable use capitals aka X
particular values of random variables use lowercase aka x
Therefore P(X = x) The rpobability that the random variable X takes particular value x
variable is **discrete** means that it can only take exact values

The **Expectation E(X)** of a variable X is a bit like the mean, but for probabilyt distributions. To find expectation you multiply each value x by the probability of getting that value and then sum the results

    E(X) = ∑xP(X = x)

