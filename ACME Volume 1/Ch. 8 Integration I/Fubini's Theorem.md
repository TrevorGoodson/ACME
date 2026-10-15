#Theorem Theorem 8.6.1
## Intuition
You can split up an integral into an integrated integral

## Technical Details
###### Assumptions
$X, Y$ are [[n-Interval]]s
$f:X \times Y \to \mathbb R$
$\int_{\cdot}d\cdot$ is the [[Multivariable Banach-Valued Integral|integral]]
$f$ is integrable
$x \in X$
$f_x : Y \to \mathbb R$ is defined by $f_x(y) = f(x,y)$
$F:X \to \mathbb r$ is defined by
$$
F(x) = \begin{cases}
\int_Y f_x(y)dy & \text{if } f_x \text{ is integrable} \\
0 & \text{else}
\end{cases}
$$

###### Conclusions
For [[Equal Almost Everywhere|almost all]] $x$, $f_x$ is integrable
$F$ is integrable on $X$
The following holds:
$$
\int_{X \times Y} f(x,y)dxdy \ = \int_X F(x)dx
$$
