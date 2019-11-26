## Probability

---

## Concepts

* Counting, Permutation, Combination
* Law of total probability, Bayes Rule
* Discrete and Continuous random variable properties
  * [Poisson Process](https://en.wikipedia.org/wiki/Poisson_point_process)
    * number of events: Poisson\(lambda t\)
    * time between events: exponential\( lambda\)
    * waiting time for k events: Gamma\(k, lambda\)
      * sum of exponential distributions\)
  * [Moment Generating functions](https://en.wikipedia.org/wiki/Moment-generating_function)
* Expectation, Covariance Theorems
  * indicator variable
  * law of total expectation
  * Jensen's Inequality
  * Conditional Expectation
* Calculus
  * p.d.f, c.d.f., variance
* Markov Process
  * equation of absorption probability
  * equation of absorption time
* Stochastic Process
  * Martingale
    * quadratic martingale \(Sn^2 - n\)
    * exponential martingale
    * stopping time and Wald's equality 
  * random walk

---

## Probability Questions

### Concepts

* example of dependent variables with zero covariance
  * Z - N\(0,1\) U +1 with 0.5 prob, -1 with 0.5 prob, X = UZ and Z are dependent

#### Card, Coin and Dice

* Coin Toss Game: A \(n+1\) coins, B n coins, probability that A has more heads than B?
  * symmetry
* 1000 coins one unfair, 10 times head toss, prob to get unfair coin
* generate fair prob by unfair coin
* Card Game: A and B pick up a card and compare, what's the probability A wins \(in tie, B wins\)
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

#### Events and Game

* put n points in a circle, the probability they all end up in a same semi-circle
  * inclusion/exclusion/mutual exclusive
* probability of triangle: stick to form a triangle
  * **\(\*\) what is the distribution of longest piece?**
    * geometric - rule of Lazy Statistician 
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

* expected number of tosses of an unfair coin to get two heads in a row
* roll a dice 3 times, can stop at any point, pay the number on dice, what's the strategy

#### Distributions

##### Bayes

* coin-making machine make coins with head prob p, p from uniform\(0,1\), whats the conditional distribution of the probability of head if you toss 1000 times and see 750 heads

##### Central Limit Theorem

* stock prices either increase by 0.2% or decrease by 0.1% with equal probability, what is the probability after 100 days it goes up twice
  * use Y as log return 

#### Process

* Drunk Passenger: 100 passengers, first 1 drunk. others will randomly pick one is seat is taken, prob your seat is taken
* Birthday  line: choose optimal position in line
* Amoeba Die out
  * recurrance
* Gambler's Ruin Problem\*: has n money, lose them all time/probability
* AB fair coin toss, toss HT in sequence wins \(first 1 to be T\)
* Basket ball game, 100 throws, prob proportional to success rate
* Observe car in 20 min interval p, prob for observing car in 5min
* Poisson Process expected waiting time
* connect 100 noodles, the prob to form a circle

---

## Stochastic Process

##### Markov Chain

* Dice game: A first dice 7-7 wins, B first dice sum of 12 wins. Probability?
* Coin Game: expected tosses to see HHH or THH?
* Color Balls\*: each time take out ball, paint first same as second, expected time to see all balls same color

##### Martingale and Random Walk

* drunk man walk on the 100 meter bridge \(at 17 meter position\), expected num of steps to walk down 
* Dice game: 1,2,3 payoff, 4,5,6 continue, expected payoff
* ticket line: 5,10 bills, no change to start with, what is the probability no extra money is needed
* coin sequence\*: toss a fail coin, expected number of tosses to get n heads in a row? 



---

### Probability Algo

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

* How to shuffle n numbers with every sequence equal probability
  * by sorting + random number sequence : O\(nlogn\)
  * Knuth Shuffle: sample without putting back \(each 1/n! probability\)
* read data in sequence, how to ensure each data has equal probability to be sampled
  * pick the first, change with 1/2 probability if there is a second ... pick n th and keep with probability n/\(n+1\), change with 1/\(n+1\)



