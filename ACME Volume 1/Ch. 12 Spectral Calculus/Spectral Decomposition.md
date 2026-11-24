#Theorem Theorem 12.6.12
## Intuition
Any matrix can be written solely in terms of its eigenvalues, eigenprojections, and eigennilpotents.
The resolvent can also be written in similar terms.
## Technical Details
###### Assumptions
$A \in M_n(\mathbb C)$
$\sigma(A)$ is the [[Spectrum]] of $A$
$\lambda \in \sigma(A)$ is an [[Eigenvalue]]
$P_{\lambda}$ is the [[Spectral Projection (Eigenprojection)]] of $A$ with regards to $\lambda$
$D_{\lambda}$ is the [[Eigennilpotent]] of $A$ with regards to $\lambda$
###### Conclusions
$A$ can be decomposed as follows:
$$
A = \underset{\lambda \in \sigma(A)}{\sum} \lambda P_{\lambda} + D_{\lambda}
$$
The resolvent of $A$ can be decomposed as follows:
$$
R(z) = \sum_{\lambda \in \sigma(A)} \left[ \frac{P_{\lambda}}{z-\lambda} + \sum_{k=1}^{m_{\lambda}-1}\frac{D_{\lambda}^k}{(z-\lambda)^{k+1}} \right]
$$
