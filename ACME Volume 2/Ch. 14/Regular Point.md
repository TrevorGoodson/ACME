#Definition Definition 14.1.2
## Intuition
A regular point is a feasible point on the equality constraint that isn't a corner or any other weird part of the set

## Technical Details
###### Assumptions
$\Omega,\ f: \Omega \to \mathbb R,\ H: \Omega \to \mathbb R^{\mathscr l},\ G : \Omega \to \mathbb R^m,\ \mathscr F$ define the [[Non-Linear Constrained Minimization Problem]] in standard form
$H \in C^1(\Omega ; \mathbb R^{\mathscr l})$ ([[Continuously Differentiable]])
$D$ is the [[Derivative]]
$x \in \mathscr F$ is the candidate for being a regular point
$\text{rank}$ is the [[Rank]]
###### Definition
$x$ is defined as a regular point if 
$$
\text{rank}(DH(x)) = \mathscr l
$$
In other words, $x$ is a regular point if $DH(x)$ has full row rank.

## Key Results
