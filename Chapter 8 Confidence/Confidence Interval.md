# For Sample Proportion
### z-distribution
$$
\hat{p}±z^*\sqrt{ \frac{\hat{p}(1-\hat p)}{n} }
$$

### A Four-Step Process

1. State: We want a C% z-interval for ...
2. Plan: We should use a one-sample Z interval.
	1. Random: The data come from a random sample.
	2. 10%: There are at least 10n ...
	3. Large Counts: $np ≥ 10, n(1-p) ≥ 10$
3. Do: Confidence Interval = ... = ... ± ... × ... = (..., ...)
4. Conclude: We are C% confident that the interval (..., ...) captures the true value. 

# For Sample Mean
### t-distribution

$$
t = \frac{{\bar{x} - \mu}}{s_{x}/\sqrt{ n }}
$$
$$
\bar{x} = t^* \frac{s_{x}}{ \sqrt{ n }}
$$
### Four-Step Process
1. State: We want a C% t-interval for ...
2. Plan: We should use a one-sample Z interval.
	1. Random: The data come from a random sample.
	2. 10%: There are at least 10n ...
	3. [[Confidence Interval#^df80a0|Normal/Large Sample]]
3. Do: Confidence Interval = ... = ... ± ... × ... = (..., ...)
4. Conclude: We are C% confident that the interval (..., ...) captures the true value. 

### Normal/Large Sample
^df80a0

1. If the distribution is Normal:
	1. The sample mean distribution is approximately Normal.
2. If the distribution is not Normal: 
	1. If the sample size is greater than 30: 
		1. The sample mean distribution is approximately Normal ([[Sample Proportion & Sample Mean#^40c847|CLT]]).
	2. If the sample size is less than 30: 
		1. According to the [[Plots#^c14237|box plot]], there is no strong skewness or outlier. We should use t-distribution with cautions.