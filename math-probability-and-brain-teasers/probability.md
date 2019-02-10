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
* prob 4 people each get an A
* **expected **number of cards to be turned over before seeing one A
* throw srictly increasing dice sequence
* roll dice, 1,2,3 game stops, pay points, expected pay off?

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
* candies in a jar: red, blue, green 10,20,30 the probability last is green
* Russian Roulette
  * the prob of first and second win
  * if spin the barrel, first and second win
  * first did not die, should you spin the barrel
  * put in two consecutive positions, first did not die
* meeting prob: arrive in 1h, meet in 5min interval
* probability of triangle: stick to form a triangle

#### Expectation, Variance, Covariance, Order Statistics

* sum of n random variables c.d.f \* 
* coupon collections N types\*
  * expected boxes to be opend
  * open n box, expected number of coupon types
    * indicator variable
* joint default probability of two random variables
* x, y \(or x_1, ..., xn\)_ follow certain distribution, the p.d.f of max\(xi\), min\(xi\) and their expectation
* correlation of max and min of x1, x2 follow distribution 
  * need to find f\(yz\) using graph
* 500 random ants expected fall down time

#### Process

* 100 passengers, first 1 drunk. others will randomly pick one is seat is taken, prob your seat is taken
* Birthday  line: choose optimal position in line
* Amoeba Die out
  * recurrance
* Gambler's Ruin Problem\*
* fair coin toss, toss HT in sequence wins
* Basket ball game, 100 throws, prob proportional to success rate
* Observe car in 20 min interval p, prob for observing car in 5min
* Poisson Process expected waiting time
* connect 100 noodles, the prob to form a circle

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



