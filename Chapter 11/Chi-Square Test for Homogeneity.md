## State
$\begin{cases} H_{0}: \text{There is no difeerence in the distributions of ......} \\ H_{a}: \text{There is a difference in the distributions of ......} \end{cases}$

## Plan
We want to perform a Chi-Square test for homogeneity.
Random: the data come from independent random samples.
	10%: there are at least 10n in the population.
Large Counts: All expected counts are at least **5**.
## Calculate the $E$
$E = \frac{\text{行总和} \times \text{列总和}}{样本总和}$

## Calculate the $\text{P-value}$
$\chi^2 = \frac{\sum(O_{i}-E_{i})^2}{E_{i}}$, where $O_{i}$ represents *Observed Value* and $E_{i}$ represents *Expected Value*.
$\text{P-value} = P(\chi^2 ≥ \text{Calculated }\chi^2) = \chi^2\text{Cdf}(\chi^2, \infty, df)$
$df = (\text{column number}-1) \times (\text{row number}-1)$

## Interpret the $\text{P-Value}$
Assuming that there is no difference in the true distributions of *(in context)*, there is a *(P-Value)* probability of observing a difference in the distributions of *(in context)* as large as or larger than the one in this study.

## Which Component Contributes to the Result the Most?
Find the largest value in the [[#^a0f2a4|stat.compmatrix]].

## Use Technology
1. Create a matrix: `menu › 7 1 1`
2. Fill out the matrix, and press `sto→ (ctrl+var)`, then enter the variable name and press `enter`.
3. Press `menu › 6 7 8`($\chi^2$ 2-Way Test...) and then select the former variable name.
4. Click OK or `enter` and check the result. 
5. To see the expected values, press `var` and then find `stat.expmatrix`.
6. To see the contribution of each component, press `var` and then find `stat.compmatrix`. ^a0f2a4

