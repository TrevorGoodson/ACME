#Theorem
Proposition 7.5.2
# Intuition
This theorem essentially creates a small expression for the relative condition number of a function that returns the root of a polynomial where the input is one of the coefficients of that polynomial (think about wiggling the coefficient and watching a root of the polynomial wiggle). 

The symbols are a bit confusing, so I'll take a stab at them here. Bold letters are functions (like $\mathbf P$), capital letters are vectors of length $n$, and lower case letters are scalars.

$\mathbf P$ is a function that takes a list of coefficients and an $x$, then spits out the value of the polynomial defined by those coefficients at $x$.

$\mathbf P_B$ is a specific polynomial defined by the coefficients in $B$ (Essentially $P$ but you fix the list of polynomials and only take $x$ as an input). Pick a root of this polynomial and call it $z$.

Now think of $\mathbf P_B$ and its root, $z$, as a starting place. Imagine how the root will move when you slightly change $B$, as in the coefficients that define $\mathbf P_B$. Some changes of $B$ will make the root disappear (think of a hump of the curve passing over the x-axis). The extent at which you can change $B$ but still has the "same" root defines a neighborhood around $B$. Call this neighborhood $\Omega$.

$\mathbf R_\Omega$ is a function that takes in a list of coefficients (that fall within $\Omega$--so it still has the "same" root as $\mathbf P_B$) and returns that root.

Now pick a list of coefficients, $A$ that fall in $\Omega$. Now pick one coefficient out of that list, call it $a_i$. $\mathbf R_{A,i}$ is a function that has the same output as $\mathbf R_\Omega$--the root of polynomials close to $\mathbf P_B$. However, instead of changing every coefficient, you just change $a_i$. You can also think of it as $\mathbf R_\Omega$ restricted to a 1-dimentional slice of $\Omega$.

The theorem states that $\mathbf R_\Omega$ is continuously differentiable. It also gives a shortcut to calculate the relative condition number of $\mathbf R_{A,i}$.
# Technical Definition
###### Declarations
$n \in \mathbb N$
$\mathbf P: \mathbb F ^{n+1} \to \mathbb F$ defined by $\mathbf P(C, x) = \sum_{i=0}^n c_i x^i$
$B \in \mathbb F^{n + 1}$ 
$\mathbf P_B: \mathbb F \to \mathbb F$ defined by $\mathbf P_B(x) = \mathbf P(B, x)$
$z$ is a [[Simple Root]] of $\mathbf P_B$

$\Omega \subset \mathbb F^{n + 1}$ such that $B \in \Omega$ ($\Omega$ is a neighborhood of $B$ in $\mathbb F^{n+1}$)
$\mathbf R_{\Omega}: \Omega \to \mathbb F$
$A \in \Omega$
$i \in \mathbb N$ such that $i \le n$
$a_i \in A$ ($a_i$ is the $i$th elements of $A$)
$b_i \in B$ ($b_i$ is the $i$th element of B)
$\mathbf R_{A,i}: \mathbb F \to \mathbb F$ is defined by $\mathbf R_{A,i}(a_i') = \mathbf R_U(A + (a_i' - a_i)e_i)$
$\kappa$ is the [[Relative Condition Number]] of $\mathbf R_{A,i}$
###### Assumptions
$\mathbf R_U(B) = z$
$\mathbf P(A, R_U(A)) = 0$ for all $A$.
###### Conclusions
$\Omega, \mathbf R_\Omega$ exist such that $\mathbf R_\Omega$ is [[Continuously Differentiable]].
Additionally, 
$$
\kappa (B,z) = \left | \frac{z^{i - 1}b_i}{\mathbf P_B'(z)} \right |
$$
