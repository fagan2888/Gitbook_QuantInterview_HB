### Calculus

1. $$(lnx^{lnx})'$$
   1. use the log trick and chain rule
2. Integrate
   1. ln\(x\)
   2. sec\(x\) 
      1. method1 : multiplies $$\frac{secx+tanx}{secx+tanx}$$
      2. method2: sec\(x\) = 1/cosx = cosx/cos^2 x = cosx / \(1- sin^2x \)
   3. E\(X\|X&gt;0\) for normal random variable
   4. **total area under curve for normal p.d.f**
      1. Calculate $$\int_{-\infty}^{\infty} e^{-x^2/2} \int_{-\infty}^{\infty} e^{-y^2/2}$$ and use polar \(rcos, rsin\) axis \(Fubini's Rule\)
3. Calculate volume/distance/mass/probability using integration
   1. snow begins 12pm, snow plow can clear constant volume per minute, 1pm moved 2miles, 2pm, 3 miles, when did the snow fall?
4. Proof
   1. Mean-Value Theorem
   2. Newton's Method
5. Concepts
   1. Remann vs Lebesgue
6. Tricks
   1. x^x^... = 2, x = ? if = 4, x = ? 

Numerical Methods

* P.D.E Implicit method, explicit method, Crank-Nickolson Method

### Probability

* x,y and x, z correlation 0.8, whats the max/min correlation for z, y? 
  * cosine similarity
  * positive semi-definite property of correlationmatrix
* generate correlated random variables
  * Cholesky decomposition $$x = \mu + R^T z$$
  * SVD decomposition $$x = \mu + UD^{\frac{1}{2}}z$$
* generate random variables with distribution
  * inverse transformation method
  * **rejection method**

Probability Algo

* How to shuffle n numbers with every sequence equal probability
  * by sorting + random number sequence : O\(nlogn\)
  * Knuth Shuffle: sample without putting back \(each 1/n! probability\)
* read data in sequence, how to ensure each data has equal probability to be sampled
  * pick the first, change with 1/2 probability if there is a second ... pick n th and keep with probability n/\(n+1\), change with 1/\(n+1\)

Monte-Carlo Simulation

* How to simulate an area of a circle
* Variance reduction techniques
  * authentic variable
  * momentum matching
  * control variate
  * **importance sampling**
  * Low-discrepancy Sequence



