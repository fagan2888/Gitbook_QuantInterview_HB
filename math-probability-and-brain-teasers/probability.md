# Probability

#### Card, Coin and Dice

* A \(n+1\) coins, B n coins, probability that A has more heads than B?
* 1000 coins one unfair, 10 times head toss, prob to get unfair coin
* generate fair prob by unfair coin
* A and B pick up a card and compare, what's the probability A wins \(in tie, B wins\)
* probability of in texas-hold'em
  * four of a kind: 0.241%
  * full house: 1.463%
  * two pairs: 4.754%
* throw srictly increasing 

#### Counting

* 11 screwy priates to lock a case, only above 5 can open 
* probability \(a+10b\)^3 last digit is 1? 
  * binomial theorem 

#### Events

* put n points in a circle, the probability they all end up in a same semi-circle
* Chess tournament: what's the probability the strongest and second strongest meet in final? 
* Bernoulli's Letter Problem
* n people in the room, what's the probability 2 has same birthday? how many people in the room to make the prob of two same birthday &gt; 1/2
* All girl world, conditional boy prob
* Dart game: 3rd dart farther than the first
  * the event nth is the best
* Monty Hall problem\*
* 
#### Expectation, Variance, Covariance and Order Statistics

#### Process

* 100 passengers, first 1 drunk. others will randomly pick one is seat is taken, prob your seat is taken
* Birthday  line: choose optimal position in line
* Gambler's Ruin Problem\*

#### Random Variables

* x,y and x, z correlation 0.8, whats the max/min correlation for z, y? 
  * cosine similarity
  * positive semi-definite property of correlationmatrix
* generate correlated random variables
  * Cholesky decomposition $$x = \mu + R^T z$$
  * SVD decomposition $$x = \mu + UD^{\frac{1}{2}}z$$
* generate random variables with distribution

  * inverse transformation method

* **rejection method**

### Probability Algo

* How to shuffle n numbers with every sequence equal probability
  * by sorting + random number sequence : O\(nlogn\)
  * Knuth Shuffle: sample without putting back \(each 1/n! probability\)
* read data in sequence, how to ensure each data has equal probability to be sampled
  * pick the first, change with 1/2 probability if there is a second ... pick n th and keep with probability n/\(n+1\), change with 1/\(n+1\)



