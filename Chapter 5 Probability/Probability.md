Probability is an **uncountable** noun.

# Basics
For any event A, $0≤P(A)≤1$.
$P(S) = \sum P(\text{every possible event})= 1$, where S represents the *sample space*.
$P(A^C) = 1-P(A)$, where $A^C$ is the complement of event A; that is, the event that A does not happen.
Mutually Exclusive: Event A and B are mutually exclusive if they have no outcomes in common, which means $P(\text{A or B}) = P(A)+P(B)$.

# Union(∪) & Intersection(∩)
Union: the probability of having at least one of them happening.
$P(\text{A or B}) = P(A \cup B) = P(A)+P(B)-P(A \cap B)$

Intersection: the probability of having both of them happening.
$P(\text{A and B}) = P(A \cap B) = P(A|B) \times P(B) = P(B|A) \times (BA)$

# Given That ( | )
![[Attachments/explanation.png]]
*\*图片未按真实比例绘制*
Given that 就是把 $P(A|B)$中的$B$的概率放大到了100%，然后求同比例放大后的$P(A \cap B)$是多少。