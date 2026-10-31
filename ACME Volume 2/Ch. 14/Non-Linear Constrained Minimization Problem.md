#Definition Introduction to Chapter 14
## Intuition

## Technical Details
###### Assumptions
$n, m, \mathscr l \in \mathbb N$
$\Omega \subset \mathbb R^n$ is [[Open]] and non-empty
$\mathscr F \subset \Omega$
$f: \Omega \to \mathbb R$ and $f$ is $C^1$ ([[Continuously Differentiable]])
$H: \Omega \to \mathbb R^{\mathscr l}$
$G : \Omega \to \mathbb R^m$
###### Definitions
The Standard form of a non-linear constrained minimization problem is defined as 
$$
\begin{array}{cc}
\underset{x \in \Omega}{\text{minimize}} & f(x) \\
\text{subject to} & G(x) \preceq 0 \\
& H(x) = 0
\end{array}
$$
$f$ is called the objective function
$H$ is called the equality constraint
$G$ is called the inequality constraint
$\mathscr F$ is called the feasible set and is defined by
$$
\mathscr F = \{ x \in \Omega \mid G(x) \preceq 0 \text{ and } H(x) = 0\}
$$
A feasible point is defined to be any element of $\mathscr F$
## Key Results
