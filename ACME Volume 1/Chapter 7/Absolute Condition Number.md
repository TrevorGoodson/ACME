#Definition 
# Intuition
The maximum slope of a function at a point

# Technical Definition
###### Declarations
$(X, \| \cdot \|_X), (Y, \| \cdot \|_Y)$ are [[Norm|normed]] [[Linearity|linear]] spaces
$f:X \to Y$
$x,y \in X$
$\delta \in \mathbb R^+$
$\lim$ is the [[Limit]]
$\sup$ is the [[Supremum]]

###### Definition
The absolute condition number of $f$ at $x$ is
$$
\hat{\kappa}(x) = \lim_{\delta \to 0^+} \sup_{||h||_X \lt \delta} \frac{||f(x + h) - f(x)||_Y}{||h||_X}
$$
# Key Results
- If $Y$ is a [[Banach Space|Banach]] space and $X$ is an [[Open]] subset of a Banach space, then $\hat{\kappa}(x) = ||Df(x)||_X$ (see [[Fréchet Derivative]]) (Proposition 7.5.3)
- If $f$ is a scalar function ($f: \mathbb R \to \mathbb R$), then $\hat \kappa (x) = |f'(x)|$ ([[Scalar Derivative]])
