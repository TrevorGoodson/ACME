The [[Lagrange Interpolation#Lagrange Basis Function|lagrange basis functions]] can be written as
$$
L_{n,j} = \frac{w_j}{(x-x_j)} \prod_{j=0}^n (x-x_j)
$$
where $w_j$ (barycentric weights) is
$$
\left( \prod_{k=0;\ k \ne j}^n (x_j-x_k) \right)^{-1}
$$
