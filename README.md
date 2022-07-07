## Bayesian Statistics in Python
___
A personal endeavor towards Bayesian Statistics. 

⚠ If your are new to this kind of Statistics: ``It is advised to also use 'pen and paper' to keep track of the equations or some of them might make your head hurt.``

This repository contains the study materials, personal remarks and experimental aspects of the book Titled: _**['Think Bayes - Bayesian Statistics in Python (2nd Edition)](https://allendowney.github.io/ThinkBayes2/index.html)'**_, written by Allen B. Downey.
___

## Chapter 1: Probability
Covers the basics of Probability with conjunctions, conditionals & laws of probability. The reader is taken through the Chapter with an Example Titled: 'Linda the Banker' involving the famous experiment by Tversky and Kahneman. The chapter takes on a single dataset and examines different aspects of it under different probabilistic theories.

**Keywords:** *conjunction, condition, commutative, probability.*
___

## Chapter 2: Bayes' Theorem
This chapter continues after the Bayes' Theorem described briefly in the former. 
Three main problems are used as examples to devise the further explanation of **Bayes' Theorem**
1. Cookie Problem: Using Bayes' Original Theorem.
2. Dice Problem: Using **Bayes Tables** and **Diachronic Bayes**
3. Monty Hall Problem: Using **Bayes Tables** and **Diachronic Bayes**

**Keywords:** *prior, likelihood, posterior, total probability, normazlization.*
___

## Chapter 3: Distributions
A python library called `empiricaldist` and it's extended class [**Probability Mass Function**](https://en.wikipedia.org/wiki/Probability_mass_function) which comes as named `Pmf` is extensively used in this chapter. Empirical distribution gives us distributions based on the data as opposed to theoretical distributions that we devised in examples from the earlier chapters. Several problems from [Chapter 2](https://github.com/iamzehan/think_bayes/blob/main/README.md#chapter-2-bayes-theorem) e.g. The Cookie Problem, Dice Problem etc. are also revisited using this distribution and it goes on show how theoretical inference differentiate and is intrecately connected to the everchanging data. A variant of the **Cookie Problem** named **Bowl 101** introduces initialization of prior hypotheses across 100 instances and then updating the posterior probability as the cookies are drawn based on the outcome(s).

**Keywords:** _Empirical Distributions, Normal Distribution, Uniform Distribution, Probabilty Mass Function._
___

## Chapter 4: Estimating Proportions
The reader is posed with a problem titled: _The Euro Problem_ and the problem is tackled using:
* Binomial Distribution, 
* Bayesian Estimation, 
* Triangle Prior and 
* The Binormial Likelihood Function
The `binom` class is used from the `scipy.stats` library for binomial distribution. However, this [Chapter](https://github.com/iamzehan/think_bayes/tree/main/Chapter%204) doesn't entirely answer the _Euro Problem_ but it intends to introduce Binomial Distribution and two types of priors and states the similiarities between the outcomes despite the differences.

**Keywords:** _Binomial Distribution, Triangle Prior, Proportions._
___

## Chapter 5: Estimating Counts
In this chapter reader is posed with a problem titled: _The Train Problem_ . This chapter answers following questions:
* What do we do when we have limited infromation but infinite possibilities?
* How does one choose prior probabilities based on the limited number of data?
* How does one count highest probable number in a situation where there chances of finding out real count is scant?

All of these questions are answered in this chapter with the problem stated above. Also _The German Tank Problem_ is referred to alongside the aforementioned. 

**Keywords:** _MMSE(Minimum Means Squared Error), Power Law Prior, Informative Prior, Uninformative Prior._
___

## Chapter 6: Odds and Addends

In this chapter there are two topics:
**Odds:** Introduces the Bayes's Rule and likelihood ratio, A Crime Problem titled- "Oliver's Blood" is solved.
**Addends:** In this part we see how to add several distributions and Central Limit Theorem with example is introduced. One more problem Titled _Gluten Sensitivity_ is solved.

**Keywords:** _odds, likelihood ratio, addends_
___
## Chapter 7: Minimum, Maximum and Mixture
In this chapter the cumulative distribution function(cdf) is introduced. Also the interchangeability between pmf and cdf is also shown. Other topics such as choosing minimum, maximum or mixture of distributions to find the optimal results of inference.

**Keywords:** _cdf, cumsum(), mixtures, minimum, maximum_
___

<i> P.S.This is a documentation of a personal journey.</i>


