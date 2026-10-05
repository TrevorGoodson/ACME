#Definition 
# Intuition
The maximum slope of a function at a point

# Technical Definition
###### Symbols
$X, Y$ are [[Norm|normed]] [[Linearity|linear]] spaces
$f:X \to Y$
$x \in X$

###### Definition
The absolute condition number of $f$ at $x$ is
$$
\hat{\kappa}(x) = \lim_{\delta \to 0^+} \sup_{||h|| \lt \delta} \frac{||f(x + h) - f(x)||}{||h||}
$$
# Key Results
- If $X, Y$ are [[Banach Space|Banach]] spaces and $U \in X$ is [[Open]], then $\hat{\kappa}(x) = ||Df(x)||$ ([[Norm]] of the [[Fréchet Derivative|derivative]]) (Proposition 7.5.3)
