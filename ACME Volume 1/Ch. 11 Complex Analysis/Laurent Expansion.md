#Theorem Theorem 11.6.8
## Intuition

## Technical Details
###### Assumptions
$\int$ is the [[Integral]]
$z_0 \in \mathbb C$
$r \in \mathbb R^+$
$R \in \mathbb R^+ \cup \{ \infty \}$
$r < R$
$A = \{ z \in \mathbb C \mid r < |z - z_0| < R\}$ (an [[Open]] annulus centered at $z_0 \in \mathbb C$ with an inner radius of $r$ and an outer radius of $R$)
$D \subset A$ is a [[Closed]] annulus contained in $A$
$f: A \to \mathbb C$ is [[Holomorphic]]
$\gamma \subset A$ is a circle
$c_n \in \mathbb C$ for each $n \in \mathbb N$ are defined by
$$
c_n = \frac1{2 \pi i} \int_{\gamma} \frac{f(w)}{(w - z_0)^{n + 1}}dw
$$
###### Conclusions
The Laurent Series of $f$, given below, converges absolutely for any $D$:
$$
f(z) = \sum_{n = -\infty}^{\infty} c_n(z-z_0)^n
$$

## Key Results
- For a given $A$ and $f$, the Laurent Series is unique (Proposition 11.6.9)

---
# Essential Part
#Definition Definition 11.7.1
## Intuition

## Technical Details
###### Assumptions

###### Definition

## Key Results
