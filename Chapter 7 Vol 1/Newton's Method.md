Theorem 7.3.4 in the book
# Intuition
It's a method to find where a function is 0.

# Technical Definition
###### Declarations
$a, b \in \mathbb R$
$f : [a, b] \to \mathbb R$ 
$\bar x \in (a,b)$
$(x_n)$ is a sequence defined as follows:
$$ x_{n+1} = x_1 - \frac{f(x_n)}{f'(x_n)}$$
###### Assumptions
$f \in C^2$ ([[Continuously Differentiable]])
$f(\bar x) = 0$
$f'(\bar x) \ne 0$
$x_0$ is "sufficiently close" to $\bar x$

###### Conclusion
$(x_n)$ converges to $\bar x$
