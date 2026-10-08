#Definition Definition 8.1.4
# Step Function
## Intuition
Chops a domain into pieces (rectangles if 2D, boxes if 3D), and is a constant function on each piece

## Technical Definition
###### Declarations
$E \subset \mathbb R^n$
$a,b,z \in \mathbb R^n$
$[a,b]$ is a [[n-Interval]]
$X$ is a [[Banach Space]]
$\mathscr P$ is a [[Subdivision]] of $[a,b]$
$I$ is an index of $\mathscr P$
$x_I \in X$ (defined for each $I$)
$R_I \subset [a,b]$ (defined for each $I$)
$s: [a,b] \to X$

###### Definitions
The indicator function, denoted $\mathbb 1_E$, is defined by
$$
\mathbb 1_E(z) = 
\begin{cases}
1, & z \in E \\
0, & z \notin E
\end{cases}
$$
$s$ is a step function if can be written as
$$
s(t) = \sum_{I \in \mathscr P} x_I \mathbb 1_{R_I} (t)
$$
for some $\mathscr P$

Note

## Key Results
- The set of all step functions, denoted $S([a, b]; X)$, is a [[Subspace]] of the [[Norm|normed]] [[Linearity|linear]] space of [[Bounded|bounded]] functions, denoted $(L^{\infty} ([a, b], X), \| \cdot \|_{L^{\infty}})$ ([[L-p Norm (Sup Norm)]]) (Proposition 8.1.5)
