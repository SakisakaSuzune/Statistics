## State
$\begin{cases} H_{0}: \text{There is no association between ... and ...} \\ H_{a}: \text{There is a association between ... and ...} \end{cases}$

## Plan
We want to perform a Chi-square test for independence.
Random: the data come from a random sample.
	10%: there are at least 10n individuals in the population.
Large Counts: all expected counts are greater than 5.

## Do
$\chi^2 = \sum \frac{(O_{i}-E_{i})^2}{E_{i}}$
$\text{P-value} = P(\chi^2 ≥ \text{Calculated } \chi^2) = \chi^2Cdf(\chi^2, \infty, df)$
$df = (\text{column number}-1) \times (\text{row number}-1)$
