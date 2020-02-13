### Monte-Carlo Simulation

* How to simulate an area of a circle
* [Variance reduction](https://en.wikipedia.org/wiki/Variance_reduction) techniques
  * authentic variable
  * momentum matching
  * control variate
  * **importance sampling**
    * $$E_{f(x)}[h(x)] = E_{g(x)}[\frac{h(x)f(x)}{g(x)}]$$
      * sample from g if hf/g has smaller variance than h\(x\)
  * Low-discrepancy Sequence

### Probability Algo

#### Random Variables

* x,y and x, z correlation 0.8, whats the max/min correlation for z, y? 
  * cosine similarity
  * positive semi-definite property of correlationmatrix
* generate correlated random variables
  * Cholesky decomposition $$x = \mu + R^T z$$
  * SVD decomposition $$x = \mu + UD^{\frac{1}{2}}z$$
* generate random variables with distribution
  * normal distribution - use Central Limit Theorem
  * inverse transformation method
  * **rejection method**

#### Shuffle

* How to shuffle n numbers with every sequence equal probability
  * by sorting + random number sequence : O\(nlogn\)
  * **Knuth Shuffle:** sample without putting back \(each 1/n! probability\)
* read data in sequence, how to ensure each data has equal probability to be sampled
  * pick the first, change with 1/2 probability if there is a second ... pick n th and keep with probability n/\(n+1\), change with 1/\(n+1\)

#### Statistics

* give Z-U\(0,1\) how to draw N\(0,1\) variable
* give Z-N\(0,1\) how to draw multi-variate \(N\(mu, sigma\)\) variable

### Numerical Methods

* P.D.E
  * Implicit method, explicit method, Crank-Nickolson Method

### 



