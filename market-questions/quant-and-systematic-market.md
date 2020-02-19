## Derivatives Pricing

#### Option price

* S, K, T-t, sigma, r, d
  * time to maturity impact of European call depends on the dividends
* Put call parity
  * synthetic forward
* American option
  * never early exercise a call
    * time value of option
      * use put-call parity
      * use replication
      * use Jensen' inequality
* [Black-Scholes formula](https://en.wikipedia.org/wiki/Black–Scholes_model)
  * assumptions
  * [Black's \(76\) formula](https://en.wikipedia.org/wiki/Black_model)
* Black-Scholes P.D.E
* Greeks
  * definition, intuition, formula
  * greeks vs spot, maturity, and strike
    * when European options have positive theta
      * deep in the money put, near maturity
  * Gamma sculpting
* Volatility surface
  * call is a convex option regarding to vol 
    * stochastic vol will increase call value
  * [local volatility models](https://en.wikipedia.org/wiki/Local_volatility)
    * Dupire-Derman-Khani
    * what is risk-neutral distribution of stock price at time T
* exotic options
  * binary option
    * price
    * delta hedge 
    * replicate \(bull spread\)
  * exchange option \(currency options\)
    * change of numerie
* option trading strategies
  * bull spread, straddle, strangle

### Fixed-Income

* Duration and Convexity
* interest rate swap
  * floater, inverse floater
* Interest rate models
  * forward rate model
    * Heath-Jarrow-Merton model
  * short-rate models
    * equilibrium models
      * Vasicek, Cox-Ingersoll-Ross model
    * no-arbitrage short-rate models
      * Hoo-Lee model
      * Hull-White model
* Bond portfolio

### Others

* Futures and forward
  * future price vs forward price
    * futures is a martingale \(stochastic interest rate and funding/reinvesting risk\)
* Risk management
  * value at risk
    * [coherent risk measures](https://en.wikipedia.org/wiki/Coherent_risk_measure)

## Factor Investing Strategies

### Concepts

* [factor investing](https://en.wikipedia.org/wiki/Factor_investing)
* information ratio
  * Sharpe, [Treynor Ratio](https://www.investopedia.com/terms/t/treynorratio.asp), Sortino, T-Sharpe
* [Information Coefficient](https://www.investopedia.com/terms/i/information-coefficient.asp)
  * [Rule of Thumb](https://financemodelsrevisited.files.wordpress.com/2015/10/fc_rule_am_law2.pdf)
  * Fundamental Law of Active Management
  * Transfer Coefficient\(\*\)

#### Passive Investing as a New Asset Class

* Smar-beta \(ETF\) and Dynamic Beta market share
  * Emerging after 2011
  * x6.4 in past 10 years
  * Increasing fast
    * Dec 16 -340 billion , \(% 36 asset owners has\) Dec-
    * 17, 410 billion \(46% asset owner has\)

#### Common Factors

**Equity Factor Strategies**

* value and momentum
  * value is debatable
  * momentum \(time-series momentum\) has defensiveness
    * long-short strategies could lose on the short position as well
* low beta
  * sensitive to market sentiment - "risk on" and "risk off"
* quality
* size
  * sensitive to "risk-on" "risk-off"

**Volatility Strategies**

* Vol Carry
  * equities: focus on hedging, intraday hedging, dynamic delta
  * Rates: treasury future,
    * OTM strangle strikes needs to be spreaded
    * multiple expiries \(vega risk smoother\) 
    * delta hedging smoothing over days \(liquidity\)
  * FX
    * long vol - US corporates, Event driven, macro hedge fungs
    * short vol - retail, European and EM corporations, dealers, ..
    * sell currency strangles: GBP, JPY USD
  * Commod
    * intraday hedging
* Dispersion
  * excess demand of index options
    * portfolio hedgers, variable annuity hedging, capital constriants, CCAR, index vol spread
  * excess supply of single name options
    * call overwriters, structured products, PB, retail
* Dynamic Gamma
* long vol, short vol strategies
  * call overwriting, calendar collar

**Rates**

* carry
  * long term rates - short term rates - roll down
* value
  * yield - inflation expecation
* momentum/trend
  * time-series of cross-sectional momentum
  * multiple windows, signal smoothing 
* more sensitive to macro-environment, eg. market sell off, currency sell off, political events, monetary policies
* common assets
  * Rates: [Government Bonds](https://en.wikipedia.org/wiki/List_of_government_bonds) bond futures

**FX**

* carry
  * implied by FX forwards
* Trend/momentum
* value
  * implied by Purchasing power parity
* assets: FX fowards

**Commodity **

* Momentum/Trend
* Carry
* Supply/demand based
  * Cogestions
  * Time Spread/Seasonalities
* Curve
* higher volatility \(supply and demand shocks\) so faster speed signals \(momentum, timespread\)
* volatility source could vary from trade-war, swine flu, weather to sugar supply, Petroleum price change

asset specific features, eg soy-bean, live cattle

#### Factor Performance Analysis

Recent Performance

Year 2017 \(Best U.S. Stock Year\) 2018\(Worst Year in most strategies\) 2019 \(bad year for equity factors \(momentum, low beta\), good for macro strategies\(FX, rates value, carry\)\)

Cross-Asset Risk Premia performance analysis usually include

* market sensitivity objectives management
  * by performance attributions - asset class
    * equities
    * TY bonds
    * credit
    * HFRXGL
    * Commodities
    * FX
* correlation management
* defensiveness study
* factor attributions

  * substrategies
    * understand how the weight change when market dynamics changed 
      * risk parity, generalized risk parity 

* #### Strategy Design
* Risk Management Spectrum

  * hedging techniques
    * intraday momentum \(short gamma position held by dealers hedging at close will revert in the morning\)

* How to test the statistical significance of a new factor/new alpha

  * statistical tests: t-test, ratio test, permutation test

* How to build factor model, deal with factor correlations

---

# Advanced

Options Trading

* Variance swap vs options selling
  * path dependency
  * volatility swap
  * correlation swap
* calendar collar
* gamma sculpting - dynamic gamma
* Dispersion trade
  * excess supply of single name option: call over-writers, structured product \(PB, retail\), Single stock volatility spread
  * excess demand of index option
    * portfolio hedger
    * variable annuity hedging
    * capital contraints, CCAR
    * index volatility spread



