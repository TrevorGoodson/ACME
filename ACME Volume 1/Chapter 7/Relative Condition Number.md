# Intuition
It is how much the function is changing scaled to be proportional to the overall size of function
# Technical Definition
###### Declarations
$X, Y$ are [[Norm|normed]] [[Linearity|linear]] spaces
$f:X \to Y$
$x,h \in X$
$\delta \in \mathbb R$
$\hat \kappa (x)$ is the [[Absolute Condition Number]] of $f$ at $x$
###### Definition
The relative condition number of $f$ at $x$ is
$$
\kappa(x) = \lim_{\delta \to 0^+} \sup_{||h|| \lt \delta} \left( \frac{||f(x + h) - f(x)||}{||h||} \bigg/ \frac{||h||}{||x||} \right) = \frac{||x||}{||f(x)||} \hat \kappa (x)
$$

# Key Results
- If $Y$ is a [[Banach Space]] and $X$ is an [[Open]] subset of a Banach space, then we have (D being the [[Fréchet Derivative]]):
$$
  \kappa(x) = \|x\| \frac{\| Df(x)\|}{\|f(x)\|}
$$