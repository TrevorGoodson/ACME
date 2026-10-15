#Theorem Theorem 8.6.9
## Intuition
Essentially the phrase: the derivative of an integral is equal to the integral of a derivative. This is for functions of two variables when the integral is in terms of one variable and the derivative is in terms of the other.
## Technical Details
###### Assumptions
$\int$ is the [[Multivariable Banach-Valued Integral|integral]]
$\frac{d}{d\ \cdot}$ is the [[Scalar Derivative]]
$\frac{\partial}{\partial \ \cdot}$ is the [[Directional Derivative|partial derivative]]
$a,b,c,d \in \mathbb R$ with $a < b$ and $c<d$
$X = (a,b)$ and $Y=[c,d]$
$x \in X$ and $y \in Y$
$f:X \times Y \to \mathbb R$
$f$ is [[Continuous]]
$\frac{\partial}{\partial x} f$ is continuous at each point $(x,y)$
###### Conclusions
$\int_c^d f(x,y)\ dy$ (which is a function from $X$ to $\mathbb R$) is differentiable at each $x$.
The following holds:
$$
\frac{d}{dx} \int_c^d f(x,y)\ dy = \int_c^d \frac{\partial}{\partial x} f(x,y)\ dy
$$
