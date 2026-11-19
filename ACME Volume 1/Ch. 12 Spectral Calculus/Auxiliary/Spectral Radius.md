#Definition Lemma 12.3.13
## Intuition

## Technical Details
###### Assumptions
$A \in M_n(\mathbb F)$
$\| \cdot \|$ is a [[Matrix Norm]]
$\lim$ is the [[Limit]]
###### Definition
The spectral radius, denoted $r(A)$, is a positive real number defined by
$$
r(A) = \lim_{k \to \infty} \|A^k\|^{1/k}
$$
## Key Results
- This limit exists (Lemma 12.3.13)
- $r(A) = \underset{\lambda \in \sigma(A)}{\sup} |\lambda|$ ([[Spectrum]], [[Supremum]]) (Corollary 12.4.7)