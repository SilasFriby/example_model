
Simulated Reality - Part 1
========================================================
author: Silas Furu Friby 
date: 2018-01-17
autosize: true


Program
========================================================

- Keywords

- $\texttt{R}$ 
  
  - $\texttt{R}$-projects
  - good to know
  - "correct" coding
  
- Version control with Git


Keywords
========================================================

- Wiener proces, Geometric brownian motion
- Ito calculus, stochastic integrals, stochastic differential equation
- Arbitrage free market and  Arbitrage free prices
- Complete market
- Risk neutral pricing, equivalent probability measures, martingales
- Monte Carlo simulation
- European call and put options 


Simple example
========================================================

Contract *A*: receive 1000 euros with probability $\frac{1}{2}$ and 0 euros with probability $\frac{1}{2}$ in one year from me 

Important question: What is the $fair$ price (today) of contract *A*?

- first of all we need to define $fair$!
- risk preferences: risk averse, risk neutral or risk loving?
- interest rate
- default probability
- and so on..


Risk-neutral pricing
========================================================

Today's dominating pricing paradigme: $\textit{Risk-neutral pricing}$, which loosely speaking says something like

$\textit{The fair price equals the expected discounted future cash flow}$
$\textit{under a risk neutral measure conditioned on the information}$
$\textit{available in the market today..}$

.. whatever that means..


Less Simple Example
========================================================

Contract $B$: receive 1000 euros if some stock index is above or equal to 100 and 0 euros if the stock index is below 100 in one year? (Finance people makes up all kinds of contracts!)

From previous slide: we need the expected future cash flow (forget about the probability measures for now)

Cash flow depends on the stock price in one year $=>$ we need to model the stock price! 


Observed stock price 2007-2018
========================================================

![some caption](sp100.png)


Simulation of Geometric Brownian Motion
========================================================

![some caption](gbm_one.png)


Understanding the underlying assumptions
========================================================

- It looks like modelling stock prices as GBMs may work!
- BUT, what are the underlying assymptions on GBMs?
- Does the real-world data live up to these assumptions?



Parameter estimation
========================================================

Model stock price as GBM $=>$ next step: estimate GBM parameters 

- Use theoretical tool box:
  * Maximum likelihood
  * Asymptotic normality
- Can we interpret anything from the estimated parameters?
- How sure are we about our estimates?
- Do the estimates tell us something about the past or future?
- Lots of questions to be answered!



Monte Carlo Simulations
========================================================

Average result from $many$ trials $\approx$ expectation (law of large numbers)

$=>$ we may find fair prices by $many$ simulations!



Monte Carlo Simulations
========================================================

![some caption](gbm.png)


Key words
========================================================

- R programming
- Continuous finance
- Computational finance
- Monte Carlo simulation
- Parameter estimation
- Backtesting
- Quantitative risk management
- Hedging


Thank you!
========================================================



<!-- Intuition about mathematical concepts -->
<!-- ======================================================== -->

<!-- - What do we mean by a filtered probability space $(\Omega, \mathcal{F}, (\mathcal{F}_t)_{t \geq 0}, P)$? -->
<!-- - What is a Brownian motion and a stocahstic differential equation? -->
<!-- - What do we mean by arbitrage-free and complete? -->
<!-- - What do we mean by a $martingale$? -->
<!-- - Why do we need both a real-world measure $P$ and a risk-neutral measure $Q$? -->
