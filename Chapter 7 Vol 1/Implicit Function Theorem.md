# Intuition
This theorem allows us to work with functions defined implicitly. If you have an equation where you can't isolate a single variable, this theorem tells you that it may still be a function from one variable to another. Use the equation to define a function of 2 variables and now work with the equation as a level set of that function.
Here's a summary of the theorem:
Consider a function $F:X \times Y \to Z$ of two variables. If it is differentiable with respect to the second variable at a certain point, and that derivative is invertible, then the level set of $F$ passing through that point defines $f: X \to Y$ implicitly around that point. Additionally, you can explicitly write $Df$ at that point in terms of $D_1 F$ and $D_2 F$.
If $X, Y$ are subsets of $\mathbb{R}$, then being invertible is equivalent to not being 0 ($F_y = D_2 F \ne 0 \Leftrightarrow F_y$ is invertible). The goal is to get a $y$ as a function of $x$ ($f:X \to Y$). So $f$ is setting $y$ in a way to keep $F$ constant as $x$ changes. Think about it like this: if you fix $x$ and wiggle $y$, $F$ does not change at a point where $F_y = 0$. So, $F$ is behaving like a function of $x$ only. So, when you change $x$, $F$ changes and a change in $y$ to keep $F$ constant. Thus, at that point, $y$ can't be written as a function of $x$.
Determinant is 0 means it's not invertible

# Technical Definition
###### Symbols
$X, Y, Z$ are [[Banach Space|Banach]] spaces
$x_0 \in U_0 \subset U \subset X$ where $U, U_0$ are [[Open|open]]
$y_0 \in V_0 \subset V \subset Y$ where $V, V_0$ are open
$k \ge 1$ is an integer
$F: U \times V \to Z$ where F is $C^k$ ([[Continuously Differentiable]])
$z_0 = F(x_0, y_0)$
$D_2F(x_0, y_0)$ is a bounded [[Linearity|linear]] operator from $Y$ to $Z$ (boundedness/linearity guaranteed by the fact $F$ is $C^k$)
$f:U_0 \to V_0$ where $F$ is $C^k$
###### Assumptions
$D_2F(x_0, y_0)$ has a bounded [[Invertible|inverse]]

###### Conclusion
$U_0 \times V_0$ and $f$ exist such that $f(x_0) = y_0$ and
$$
\{(x,y) \in U_0 \times V_0 \mid F(x,y)=z_0 \} = \{(x, f(x)) \mid x \in U_0\}
$$
And
$$
Df(x) = - D_2 F(x, f(x))^{-1} D_1 F(x,y)
$$
on $U_0$

# Key Results
- It is equivalent to the Inverse function theorem