Also called the total derivative.
A more general derivative than the [[Directional Derivative]]

# Intuition
Given a function $f:X \to Y$, the Fréchet derivative shows how the output is changing relative to the input. You typically only talk about a derivative at a certain point in the domain, so $Df(x): X \to Y$ also. But, you can think of the derivative of the function as a whole, so $Df: X \to (X \to Y)$, which can be a little confusing depending on the function

# Technical Definition
###### Declarations
$(X, || \cdot ||_X), (Y, || \cdot ||_Y)$ are [[Banach Space|Banach]] spaces
$x, h \in X_0 \subset X$ where $X_0$ is [[Open]]
$f: X_0 \to Y$
###### Definition
The Fréchet Derivative, $Df$, is a linear transformation that satisfies:.
$$
\lim_{h \to 0}\frac{||f(x+h)-f(x)-Df(h)||_Y}{||h||_X} = 0
$$
