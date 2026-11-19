#Definition Example 5.7.3
## Intuition

## Technical Details
###### Assumptions
$A \in M_n(\mathbb F)$
$\| \cdot \|$ is the [[Induced Matrix Norm (Operator Norm)]]
$\| A \| < 1$
###### Definition
The Neumann Series is defined to be the following sum:
$$
\sum_{k=0}^{\infty} A^k
$$

## Key Results
$$
\sum_{k=0}^{\infty} \| A^k \| \le \sum_{k=0}^{\infty} \| A \|^k = \frac{1}{1 - \|A\|}
$$
(Example 5.7.3)
$$
\sum_{k=0}^{\infty} A^k = (I-A)^{-1}
$$
([[Inverse]]) (Proposition 5.7.4)