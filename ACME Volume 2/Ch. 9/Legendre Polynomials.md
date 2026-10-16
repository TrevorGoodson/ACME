#Definition Section 9.3.1
## Intuition

## Technical Details
###### Assumptions
$\langle \cdot, \cdot \rangle$ is the [[Inner Product]] defined by
$$
\langle f,g \rangle = \int_{-1}^1 f(x)g(x)\ dx
$$



###### Definition
$u_0 = 1$, $u_1 = x$, $u_2 = x^2 - \frac 13$ and
$$
u_k = x^k - \sum_{j=0}^{k-1} \frac{\langle u_j, x^k \rangle}{\langle u_j, u_j \rangle} u_j
$$


## Key Results
- $\{u_0, \dots, u_n \}$ forms an [[Orthogonal]] set
