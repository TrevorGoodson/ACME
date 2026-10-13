#Definition Definition 11.3.1
## Intuition
How off
## Technical Details
###### Assumptions
$n,m \in \mathbb N$
$f: \mathbb F^n \to \mathbb F^m$
$x \in \mathbb F^n$
$\| \cdot \|$ is some [[Norm]] on $\mathbb F^m$
$\tilde f(x)$ is the computed value of $f(x)$ given some numerical implementation of $f$

###### Definition
The relative forward error, denoted $\epsilon _{\tilde f}$, is defined by
$$
\epsilon _{\tilde f} = \frac{\| f(x) - \tilde f(x) \|}{\|f(x)\|}
$$
