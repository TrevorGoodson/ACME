# Lagrange Basis Function
#Definition Theorem 9.2.6
The Lagrange basis functions are defined as
$$
L_{n,j}(x) = \prod_{k=0, k \ne j}^{n} \frac{x-x_k}{x_j-x_k}
$$
# Interpolating Polynomial
#Theorem Theorem 9.2.6
The Lagrange basis functions can be used to construct an interpolating polynomial
$$
p(x) = \sum_{j=0}^n y_j L_{n,j}(x)
$$

## Key results
- Sampling $n+1$ points from an $n$th degree polynomial, the Lagrange interpolation through those points yields the original polynomial exactly (Corollary 9.2.10)