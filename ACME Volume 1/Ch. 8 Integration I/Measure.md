#Definition Definition 8.1.6
## Intuition
The measure of a set is the same thing as length for 1D, area for 2D, and volume for 3D.

## Technical Definition
###### Declarations
$n \in \mathbb N$
$j \in \{a, \dots, n\}$
$a_j, b_j \in \mathbb R$ with $a_j < b_j$ (defined for each $j$)
$A_j \subset \mathbb R$ is defined as one of the following: $[a_j,b_j], (a_j,b_j), (a_j,b_j]$ or $[a_j,b_j)$ (defined for each $j$)
$R = A_1 \times \cdots \times A_n \in \mathbb R^n$ ([[Cartesian Product]])
###### Definition
The measure of $R$, denoted $\lambda (R)$, is defined by
$$
\lambda (R) = \prod_{j=1}^n (b_j - a_j)
$$