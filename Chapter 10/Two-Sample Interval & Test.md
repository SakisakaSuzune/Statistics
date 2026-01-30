#Chapter_10
## Distribution of $\hat{p_{1}}-\hat{p_{2}}$
1. $\mu_{\hat{p_{1}}-\hat{p_{2}}} = \mu_{\hat{p_{1}}} - \mu_{\hat{p_{2}}} = p_{1}-p_{2}$  ←(unbiased estimator)
2. $\sigma_{\hat{p_{1}}-\hat{p_{2}}} = \sqrt{ \sigma_{\hat{p_{1}}}^2 + \sigma_{\hat{p_{2}}}^2 } = \sqrt{ \frac{p_{1}(1-p_{1})}{n_{1}} + \frac{p_{2}(1-p_{2})}{n_{2}}}$, where $\begin{cases} n_{1} ≤ \frac{1}{10}N_{1} \\ n_{2} ≤ \frac{1}{10} N_{2}\end{cases}$  (10% rule).
3. $\hat{p_{1}}-\hat{p_{2}} ～ N(p_{1}-p_{2}, \sqrt{ \frac{p_{1}(1-p_{1})}{n_{1}} + \frac{p_{2}(1-p_{2})}{n_{2}}})$ , where $\begin{cases} n_{1}p_{1}≥10, n_{1}(1-p_{1})≥10 \\ n_{2}p_{2}≥10, n_{2}(1-p_{2})≥10 \end{cases}$ (Large Counts).
## Conditions for a Two-Sample z Interval/Test
1. **Random**: The data come from two independent well-designed random samples. 
	**10%**: When sampling without replacement, check that $\begin{cases} n_{1} ≤ \frac{1}{10}N_{1} \\ n_{2} ≤ \frac{1}{10} N_{2}\end{cases}$ .
2. **Large Counts**: $\begin{cases} n_{1}p_{1}≥10, n_{1}(1-p_{1})≥10 \\ n_{2}p_{2}≥10, n_{2}(1-p_{2})≥10 \end{cases}$ .
## C% CI for $p_{1}-p_{2}$
1. $(\hat{p_{1}}-\hat{p_{2}}) ± z^* · \sqrt{ \frac{p_{1}(1-p_{1})}{n_{1}} + \frac{p_{2}(1-p_{2})}{n_{2}}}$
## Test for $p_{1}-p_{2}$
1. **State**: $\begin{cases} H_{0}: p_{1}-p_{2} = \dots \\ H_{a}: p_{1}-p_{2} ><≠ \dots \end{cases}$ , where $p_{1}$ represents ..., $p_{2}$ represents ....
2. **Plan**: We want to perform a two-sample z test for $p_{1}-p_{2}$. 
		**Random**: The data come from two independent well-designed random samples. 
		**10%**: When sampling without replacement, $\begin{cases} n_{1} ≤ \frac{1}{10}N_{1} \\ n_{2} ≤ \frac{1}{10} N_{2}\end{cases}$ .
		**Large Counts**: $\begin{cases} n_{1}\hat{p_{1}}≥10, n_{1}(1-\hat{p_{1}})≥10 \\ n_{2}\hat{p_{2}}≥10, n_{2}(1-\hat{p_{2}})≥10 \end{cases}$ . ←(use $\hat{p_{1 }}$ instead of $p_{1}$)
3. **Do**: $z = \dfrac{(\hat{p_{1}}-\hat{p_{2}}) - 0}{\sqrt{ \dfrac{\hat{p_{c}}(1-\hat{p_{c}})}{n_{1}} + \dfrac{\hat{p_{c}}(1-\hat{p_{c}})}{n_{2}}}}$
4. **Conclude**: ...
### $\hat{p_{c}}$ ???
**Pooled/Combined Proportion**
$\hat{p_{c}} = \dfrac{n_{1}\hat{p_{1}} + n_{2}\hat{p_{2}}}{n_{1} + n_{2}}$ 

---------------------------
## Distribution of $\bar{x_{1}}-\bar{x_{2}}$
1. $\mu_{\bar{x_{1}}-\bar{x_{2}}} = \mu_{\bar{x_{1}}} - \mu_{\bar{x_{2}}} = \mu_{1} - \mu_{2}$
2. $\sigma_{\bar{x_{1}}-\bar{x_{2}}} = \sqrt{ \sigma_{\bar{x_{1}}}^2 + \sigma_{\bar{x_{2}}}^2 } = \sqrt{ \frac{S_{x_{1}}^2}{n_{1}} + \frac{S_{x_{2}}^2}{n_{2}} }$, where $\begin{cases} n_{1} ≤ \frac{1}{10}N_{1} \\ n_{2} ≤ \frac{1}{10} N_{2}\end{cases}$ (10% rule).
3. $(\bar{x_{1}}-\bar{x_{2}}) ～ t$, where $df = min\{n_{1}, n_{2}\}$.
	**Normal/Large Sample**: $\begin{cases} n_{1}≥30 \\ n_{2}≥30 \end{cases}$.
## C% CI for $\mu_{1}-\mu_{2}$
$\bar{x_{1}}-\bar{x_{2}} ± t^* · \sqrt{ \frac{S_{x_{1}}^2}{n_{1}} + \frac{S_{x_{2}}^2}{n_{2}}}$
1. **State**: we want a C% confidence interval.
2. **Plan**: we should use a two-sample t interval.
		**Random**: the data come from two random independent samples.
		**10%**:  $\begin{cases} n_{1} ≤ \frac{1}{10}N_{1} \\ n_{2} ≤ \frac{1}{10} N_{2}\end{cases}$ 
		**Normal/Large Sample**
## Test for $\mu_{1}-\mu_{2}$
1. **State**: $\begin{cases} H_{0}: \mu_{1}-\mu_{2} = \dots \\ H_{a}: \mu_{1}-\mu_{2} ><≠\dots\end{cases}$
2. Plan: 
		Random
		10%
		Normal/Large Sample
3. Do: $t = \frac{{(\bar{x_{1}} - \bar{x_{2}}) - (\mu_{1}-\mu_{2})}}{\sqrt{  \frac{S_{x_{1}}^2}{n_{1}} + \frac{S_{x_{2}}^2}{n_{2}} }}$ 
4. Conclude