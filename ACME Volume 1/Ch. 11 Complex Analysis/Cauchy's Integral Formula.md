#Theorem Theorem 11.4.1
## Intuition
This theorem is used when you have an integral of a specific form. You don't have to integrate anything to evaluate the integral, you can just use this expression to substitute the integral for a direct function call.

## Technical Details
###### Assumptions
$X$ is a [[Banach Space]] over $\mathbb C$
$U \subset X$ is [[Simply Connected]] and [[Open]]
$f:U \to X$ is [[Holomorphic]]
$\gamma \subset U$ is a simple closed [[Contour]] (traversed once counterclockwise)
$z_0 \in U$ such that it is in the interior of $\gamma$
###### Conclusions
$$f(z_0) = \frac{1}{2\pi i} \oint_{\gamma} \frac{f(z)}{z - z_0} \, dz.$$

## Key Results
