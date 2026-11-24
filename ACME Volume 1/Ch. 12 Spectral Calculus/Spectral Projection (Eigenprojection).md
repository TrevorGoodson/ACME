#Definition 
## Intuition

## Technical Details
###### Assumptions
$\int \cdot\ d \cdot$ is the [[Integral]]
$z \in \mathbb C$
$A \in M_n(\mathbb C)$
$\sigma(A)$ is the [[Spectrum]] of $A$
$\lambda \in \sigma(A)$
$\Gamma \subset \mathbb C$ is a [[Contour|simple closed contour]] with $\lambda$ on the interior but no other element of $\sigma(A)$ 
$\text{Res}(\cdot)$ is the [[Residue]]
$R(\cdot)$ is the [[Resolvent]]
###### Definition
The spectral projection of $A$ with regards to $\lambda$, denoted $P_{\lambda}$, is defined to be
$$
P_{\lambda} = \text{Res}(R(z), \lambda) = \frac1{2\pi i} \int_{\Gamma} R(z)\ dz
$$

## Key Results
#### Idempotence
$P_{\lambda}$ is a [[Projection]] (Theorem 12.4.2)
$$
P_{\lambda}^2 = P_{\lambda}
$$
#### Independence
$P_{\lambda}P_{\lambda'} = P_{\lambda'}P_{\lambda} = 0$ for any $\lambda, \lambda' \in \sigma(A)$ with $\lambda \ne \lambda'$ (Theorem 12.4.2)
#### A-invariance
$$
AP_{\lambda} = P_{\lambda}A
$$
(Theorem 12.4.2)
#### Completeness
$$
\sum_{\lambda \in \sigma(A)} P_{\lambda} = I
$$
(Theorem 12.4.2)
