# Intuition
A uniform contraction mapping is actually a family of functions. You can think of it like a single function of two variables $f: D \times B \to D$ (like the technical definition below), or you can think of it a bunch of functions $f_b : D \to D$ that are "parameterized" by $b$. Each function shares a universal shrinkage factor (less than 1) that bounds above the ratio between the distance between two outputs and the distance between the inputs. This is why it's uniform: each function shares the same shrinkage factor regardless of $b$.
# Technical Definition
###### Declarations
$D$ is a [[Norm|normed]] [[Linearity|linear]] space
$B$ is any set
$f: D \times B \to D$ 
$x_1, x_2 \in D$
$b \in B$
$\lambda \in [0, 1)$

###### Definition
$f$ is a uniform contraction mapping if $\lambda$ exists such that
$$
||f(x_2, b) - f(x_1, b)||_X \le \lambda ||x_2 - x_1||_X
$$
for all $x_1, x_2, b$.