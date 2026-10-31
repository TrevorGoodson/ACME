#Definition Example 3.5.7, Example 1.1.6
## Intuition
The L-p space is the set of functions that are well behaved in some way. When $p$ is $\infty$, the L-p space is the set of all bounded functions on a certain domain.

## Technical Details
###### Assumptions
$p \in \mathbb R$ such that $p \ge 1$ or $p = \infty$
$[a,b]$ is a [[n-Interval]] (often just a normal interval)
$(X, \| \cdot \|)$ is a [[Norm|normed]] [[Linear]] space (often just a subspace of $\mathbb F$)
$f:[a,b] \to X$
$\int$ is the [[Multivariable Banach-Valued Integral|integral]]
###### Definition
For the $L^p$ space with regards to $[a,b]$ and $X$, denoted $L^p([a,b];X)$ or $L^{\infty}([a,b];X)$, is defined as the set of all functions from $[a,b]$ that satisfy
$$
L^p([a,b]; X) = \left\{f:[a,b] \to X \ \ \middle\vert \ \ \int_a^b |f(x)|^p dx < \infty \right\} \text{ for } p \ne \infty
$$
$$
L^{\infty} ([a,b]; X) = \left\{f:[a,b] \to X \ \ \middle\vert \ \ \sup_{x \in [a,b]}|f(x)| < \infty \right\} \text{ for } p = \infty
$$
The [[Norm]] on $L^p([a,b];X)$, denoted $\|f\|_{L^p}$ or $\|f\|_{L^{\infty}}$, is defined as follows
$$
\| f \|_{L^p} = \left( \ \int_a^b |f|^p dx \ \right)^{1/p} \ \ \ \text{ for } p \ne \infty
$$
$$
\| f \|_{L^{\infty}} = \sup_{x \in [a,b]} |f(x)| \ \ \ \text{ for } p = \infty
$$
## Key Results
- $L^p$ is a [[Vector Space]] (Example 1.1.6 (iv))
- $(L^{\infty} ([a, b], X), \| \cdot \|_{L^{\infty}})$ is a [[Norm|normed]] [[Linear|linear]] space & contains all [[Bounded|bounded]] functions on $[a,b]$ ($X$ is any normed space)
- $\| \cdot \|_{L^{\infty}}$ is often called the sup-norm
