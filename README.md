# DSS6-Statistical-Inference-Week4

# Project 1 - Central Limit Theorem Exploration

In this project I investigate the exponential distribution in R and compare it with the Central Limit Theorem. The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. The mean of an exponential distribution is 1/lambda and the standard deviation is also 1/lambda. I set lambda = 0.2 for all of the simulations. I investigate the distribution of averages of a sample containing 40 draws from an exponential distribution. I create 1000 such averages (1000 simulations of 40 data points each).

I illustrate via simulation and associated explanatory text the properties of the distribution of the mean of 40 exponentials. I will:
* Show the sample mean and compare it to the theoretical mean of the distribution.
* Show how variable the sample is (via variance) and compare it to the theoretical variance of the distribution.
* Show that the distribution is approximately normal.
* In point 3, I focus on the difference between the distribution of a large collection of random exponentials and the distribution of a large collection of averages of 40 exponentials.

# Project 2 - ToothGrowth Data Exploration

Now I'm going to analyze the ToothGrowth data in the R datasets package.

I will:
* Load the ToothGrowth data and perform some basic exploratory data analyses
* Provide a basic summary of the data.
* Use confidence intervals and/or hypothesis tests to compare tooth growth by supp and dose.
* State my conclusions and the assumptions needed for my conclusions.