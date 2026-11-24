#Definition
Definition 7.5.12

# Intuition
The condition number of a matrix, $A$, bounds all 3 of these functions:
$$
f(x) = Ax \Biggm | g(A) = Ax \Biggm | h(b) = A^{-1}b
$$
So, you can just say "condition number" without specifying which function, since they all behave similarly enough
# Technical Definition
###### Declarations
$A \in M_n(\mathbb F)$

###### Definition
The condition number of $A$, $\kappa (A)$ satisfies
$$
\kappa (A) = \| A \| \| A^{-1} \|
$$
