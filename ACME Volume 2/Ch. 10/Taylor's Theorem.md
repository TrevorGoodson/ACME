#Theorem Theorem 10.3.7
## Intuition
This theorem essentially says that a Taylor's polynomial is a good approximation of a function. Taylor's theorem constructs a limit for how wrong a Taylor's approximation can be. The theorem labels the error $R_k$. The bound on $R_k$ is written in terms of $k$, which is the order of the approximation, $h$, which is how far away from the initial point the approximation is being used, and $M$, which is a bound on the $k$th derivative of $f$ (the function being approximated).

## Technical Details
###### Assumptions
$U \subset \mathbb F$ is [[Open]]
$f: U \to \mathbb F$ with $f \in C^k(U; \mathbb F)$ ([[Continuously Differentiable]])
$f^{(k)}$ refers to the $k$th [[Scalar Derivative|derivative]] of $f$
$z \in U$
$h \in \mathbb F$
$\mathscr l(z, z+h) = \{z + th \mid 0 \le t \le 1 \}$
Restrict $h$ such that $\mathscr l \subset U$
$M \in \mathbb R^+$
$R_k \in \mathbb F$
###### Conclusions
$f^{(k)}$ must be [[Bounded]] on $\mathscr l$, set $M$ to be that bound (this follows from $\mathscr l$ being [[Compact set|compact]])
$|R_k| \le \frac{M}{k!}|h|^k$.
Finally, we have
$$
f(z + h) = f(z) + f'(z)h+ \frac12f''(z)h^2 + \cdots + R_k
$$
