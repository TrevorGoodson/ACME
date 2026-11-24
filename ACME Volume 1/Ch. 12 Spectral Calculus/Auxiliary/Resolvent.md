#Definition Definition 12.3.1
## Intuition
A function that takes in a complex number and spits out a matrix. Obtained by taking the inverse of $zI - A$. ($z$ is the input)
## Technical Details
###### Assumptions
$A \in M_n(\mathbb C)$
$\rho(A)$ is the [[Resolvent Set]]
$z \in \rho(A)$
$(\cdot)^{-1}$ is the [[Inverse]]

###### Definition
The resolvent of $A$, denoted $R(A, \cdot)$, is a map $\rho(A) \to M_n(\mathbb C)$ given by
$$
R(A,z) = (zI-A)^{-1}
$$

## Key Results
#### Relationship to Adjugate & Determinant
$$ R(z) = \frac{\text{adj}(zI-A)}{\text{det}(zI-A)} $$
([[Adjugate]], [[Determinant]]) (Remark 12.3.3)