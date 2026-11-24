#Definition Definition 11.7.6
## Intuition
A value (can be a matrix or a scalar) that is computed by taking a contour integral of a function around a point, then dividing by $2\pi i$.
## Technical Details
###### Assumptions
$z_0 \in \mathbb C$
$r \in \mathbb R$ with $r > 0$
$A = B(z_0,r) \setminus \{z_0\}$ (a punctured ball centered at $z_0$)
$\gamma \subset A$ is a [[Contour|simple closed contour]] that surrounds $z_0$
$\int \cdot\ d \cdot$ is the [[Integral]]
$f: A \to \mathbb C$ is [[Holomorphic]]
###### Definition
The residue of $f$, denoted $\text{Res}(f,z_0)$, is defined to be
$$
\frac1{2\pi i} \int_{\gamma} f(z)\ dz
$$

## Key Results
- $\text{Res}(f, z_0) = c_{-1}$, the $-1$ coefficient from the [[Laurent Expansion]]
