bayesian
================
Amr Attyah
12/31/2018

Problem 1
---------

Management at a call center is investigating the call load in order to find an efficient staffing policy. Assume that time intervals between calls are exponentially distributed. Assume the mean time between calls is constant during the mid-morning period. The following sequence of call times was collected during mid-morning, measured in seconds after the start of data collection: 168, 314, 560, 754, 1215, 1493, 1757, 1820, 1871,1982, 2134, 2430, 3187, 3388, 3485. Assume an inverse Gamma prior distribution with shape a =4 and scale b = 0.0015 for the mean time in seconds between calls Q. Find the posterior distribution for Q. Find the prior and posterior mean and standard deviation for Q. Discuss. (Note: Because of the memoryless property of the exponential distribution, you can treat the time until the first call as having an exponential distribution.)

![](bayesian_files/figure-markdown_github/unnamed-chunk-1-1.png)

Starting with a very small beta resulted in a very spread out inverse gamma distribution with mean 222.22 and a large standard deviation of 157.1. Using the exponential data, which is the conjugate pair of the inverse gamma, we updated our beliefs to have a mean of 230 and standard deviation of 55.91. The graph displayed about confirms the findings that the posterior distribution is narrower and and more concentrated.
