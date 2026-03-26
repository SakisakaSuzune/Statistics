m$\hat{y}=\alpha+\beta x$ (population regression line)
$\hat{y}=a+bx$ (sample regression line)

$\hat{y}$ 是估计值，所以才会带 $\hat{}$ 。

$y_{i}=\alpha+\beta x_{i}+\epsilon_{i}$ , $\epsilon_{i}$ 就是residual。
$\epsilon_{i} ～ N(0, \sigma)$

# $\hat{y}=a+bx$
1. $\mu_{b}=\beta$ 
2. $\dfrac{\sigma}{\sigma_{x}\sqrt{ n }}$
	10% condition: $n≤ \frac{1}{10} N$
3. $b ～ N\left( \beta, \frac{\sigma}{\sigma_{x}\sqrt{ n }} \right)$

# Conditions for Regression Inference
1. **Linear**: The actual relationship between x and y is linear. 
	No leftover pattern in the residual plot.
2. **Independent**
	10% condition *or ...*
	knowing the result of one observation does not help to predict the value of another observation. (没有random sample时)
3. **Normal**: The residual distribution is Normal with any x.
	The histogram of residuals is unimodal and roughly symmetric *or ...*
	the histogram of residuals shows no strong skewness or outliers. (不符合上一行时)
4. **Equal SD**: The SD of residual is the same with any x.
	The residual plot shows roughly equal scatter of all values of x.
5. **Random**: All data come from a random sample / randomized experiment.


Regression line relating y to x.

Confidence Interval: $b ± t_{n-2} \times SE_{b}$
Test Statistic: $t=\frac{{b-\beta_{0}}}{SE_{b}}$
