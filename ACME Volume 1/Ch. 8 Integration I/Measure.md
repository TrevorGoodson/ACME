#Definition Definition 8.1.6
## Intuition
The measure of a set is the same thing as length for 1D, area for 2D, and volume for 3D.

## Technical Details
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

# Measure Zero
#Definition Definition 8.3.1
## Intuition
A set has a measure of 0 if it doesn't have any "volume". Intervals in 2D are squares, but if one side length is 0, then it's area (measure) is 0. A square in 3D has no volume, so it's measure is 0.
## Technical Details
###### Assumptions
$A \in \mathbb R^n$
$\epsilon \in \mathbb R_{>0}$
$(I_k)_{k=0}^{\infty}$ is a collection of [[n-Interval]]s
$\lambda$ is the measure (see above)

###### Definition
$A$ is defined to have measure zero if the following hold for some $I_k$ and all $\epsilon$:
$$A \subset \bigcup_{k=0}^{\infty} I_k$$
and
$$
\sum_{k=0}^{\infty} \lambda (I_k) < \epsilon
$$
