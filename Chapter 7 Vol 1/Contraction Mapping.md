#Definition
# Intuition
A function that shrinks the distance between inputs. In other words, brings inputs closer together.

# Technical Definition
###### Symbols
$D$ is a [[Norm|normed]] [[Linearity|linear]] space (or a subset of one)
$x,y \in D$
$f$ is a function $D \to D$
$k \in [0,1)$

###### Definition
$f$ is a contraction mapping if there exists $0 \le k \lt 1$ such that
$$
||f(x) - f(y)|| \le k||x - y||
$$
for all $x,y$

# Key Results
- Contraction mappings are [[Lipschitz]] [[Continuous]] with constant $k$
- There exists a fixed point of $f$ (this is called the contraction mapping principle)
