Theorem 7.4.8
# Intuition
If the derivative is invertible at a point, then the function is too (locally).
This theorem also says that the derivative of the inverse is equal to the inverse of the derivative
# Technical Definition
###### Declarations
$X, Y$ are [[Banach Space|Banach]] spaces
$x_0 \in U_0 \subset U \subset X$ where $U, U_0$ are [[Open]]
$y_0 \in V_0 \subset V \subset Y$ where $V_0, V$ are open
$f : U \to V$  such that $f(x_0) = y_0$
$g:V_0 \to U_0$
###### Assumptions
$f \in C^k$ ([[Continuously Differentiable]])
$Df(x_0) \in \mathcal{B}(X;Y)$ (the [[Fréchet Derivative|derivative]] is bounded and [[Linearity|linear]]; follows from $f \in C^k$)
$Df(x_0)$ has a bounded [[Invertible|inverse]]

###### Conclusions
There exists unique $g \in C^k$ that is the inverse to $f$. In other words, $\forall y \in V_0, f(g(y)) = y$ and $\forall x \in U_0, f(g(x)) = x$.
Additionally $\forall y \in V_0$
$$
Dg(y) = [Df(g(y))]^{-1}
$$

