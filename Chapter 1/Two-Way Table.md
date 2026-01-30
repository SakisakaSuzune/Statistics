
↓Row Variable    ↓Column Variable

|                   | Male | Female | Total |
| ----------------- | ---- | ------ | ----- |
| **Perspective A** | 10   | 40     | 50    |
| **Perspective B** | 20   | 30     | 50    |
| **Perspective C** | 30   | 20     | 50    |
| **Perspective D** | 40   | 10     | 50    |
| **Total**         | 100  | 100    | 200   |

## Marginal/Conditional Distribution
Marginal Distribution: the probability distribution of a subset of variables, ignoring the rest.
	$P(\text{Male}) = {\displaystyle \sum P(\text{Male},\text{Perspectives}) } = \frac{10}{200}+\frac{20}{200}+\frac{30}{200}+\frac{40}{200} = \frac{100}{200}$
	To calculate a marginal distribution, add numbers in a row or a column to their sum. 
	e.g. Marginal distribution of Gender: $\text{100 Females and 100 Males}$

Conditional Distribution: The probability distribution of a variable given that another variable is known or fixed. 
	$P(\text{Male}|\text{Perspective A}) = \frac{P(\text{Male},\text{Perspective A})}{P(\text{Perspective A})} = \frac{10}{50}$
	To calculate a conditional distribution, calculate the proportion of a variable in a given variable.
	e.g. Condition Distribution of Perspectives (Given Male): $\text{10 Perspective A, 20 Perspective B, 30 Perspective C, 40 Perspective D}$
