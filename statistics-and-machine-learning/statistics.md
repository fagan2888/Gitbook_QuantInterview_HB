# Concepts

### Descriptive Statistics

* Univariate Statistics
  * shape: variance, [skewness](https://en.wikipedia.org/wiki/Skewness), [kurtosis](https://en.wikipedia.org/wiki/Kurtosis)
  * center: mean, median, mode
  * spread: standard deviation, [entropy](https://en.wikipedia.org/wiki/Entropy_%28information_theory%29)
  * relative position
* Bivariate Statistics
  * correlation, covariance
    * shrinkage
    * [spearman correlation](https://en.wikipedia.org/wiki/Spearman%27s_rank_correlation_coefficient)
    * [chi-square statistics](https://en.wikipedia.org/wiki/Chi-squared_test)
    * limits of correlation/covariance
      * measures linear relationship
      * dependent variables not correlated
  * regression methods
* multivariate

### Statistical Inference

* Independence and Correlation
  * dependent but zero correlation
    * X, X^2 \(normal, Chi-square\)
* Law of Large Number
* Central Limit Theorem
  * i.i.d. assumption
  * regularization condition
  * convergence rate
* Estimation
  * Method of Moments
  * MLE
    * calculation: 
      * exponential dist MLE
      * binomial MLE \(variance, used in Monte Carlo\)
    * What is Fisher Information
      * cutting variance to half, double the sample size
  * Consistency
  * Confidence Interval
    * the interval is random, the parameter is fixed
* Hypothesis Test
  * Type I error, significance \(precision\)
  * Type II error, power \(recall\)
  * how to test multiple hypothesis\(FWER vs FDR\)
* Statistical Testing
  * 1 Group
    * binary test, t-test
  * 2 Groups
    * t-test
    * dep-groups t-test
  * ANOVA
  * what if p=thredhold\(0.05\)
    * it's up to you
* Bias-Variance Decomposition
* Computational Approach
  * Permutation Test
  * BootStrapping
    * what is the percentage left out of sample? \(N -&gt; inf for sampling times and sample size\)

### Random Numbers

* Use Random\(5\) to generate Random\(25\) / Random\(21\) \(use 5 \* random\(5\) + random\(5\)\)
  * two-dimensional matrix + sample with replacement

### Time Series Analysis

Steps

1. Plot the time series
2. Transform to stationary pcoress
   1. Box-Cox \(log\) transformation
   2. trend, seasonality, sharp changes, outliers
3. Fit the model
4. Diagnostic checks
5. Generate forcasts
6. Invert transformation to transform forecast back to original series

Derive

* mean, autocovariance of

* AR\(1\)
* MA\(1\)
* 


