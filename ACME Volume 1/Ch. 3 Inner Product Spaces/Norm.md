#Definition Definition 3.5.1
## Intuition
A norm is kind of like the length of something, but defined to be generalized to settings where the idea of length loses its meaning. 
## Technical Details
###### Assumptions
$V$ is a [[Vector Space]]
$x,y \in V$
$a \in \mathbb F$
###### Definition
A norm, denoted $\| \cdot \|$, is a map from $V$ to $\mathbb R$ defined by the following conditions:
- Positivity: $\|x\| \gt 0$ if $x \ne \mathbf 0$; $\|x\| = 0$ if $x = \mathbf 0$
- Scale preservation: $\|ax\| = |a|\|x\|$
- Triangle inequality: $\|x+y\| \le \|x\| + \|y\|$
## Key Results
- On $\mathbb R$, the norm is the absolute value function ($| \cdot |$)


## Examples
### Norm of a Bounded Linear Transformation
![[Bounded Linear Transformation#Technical Details|Induced Norm]]
### Norm of a Matrix (Induced Matrix Norm)
![[Induced Matrix Norm]]
### Matrix Norm
Definition 3.5.15