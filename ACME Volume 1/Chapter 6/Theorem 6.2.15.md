The [[Directional Derivative|derivative]] of $f$ in the direction of $v$ at $x$ is equal to the [[Fréchet Derivative|total derivative]] at $x$ of $v$. 
$$
D_vf(x) = Df(x)v
$$
You have to set $x$ to be in an open set within $X$
Remember the domains & codomains of everything here.
$f:X \to Y$
$D_vf: X \to Y$
$D_vf(x) \in Y$
$Df:X \to (X \to Y)$
$Df(x): X \to Y$
$Df(x)v \in Y$
You can think of $Df(x)$ as a matrix of the same shape of $f$. Thus, $Df(x)v$ is just matrix multiplication. This theorem is restricted to $\mathbb{R}^n$, which is why the notation is like it is. I think it still holds generalized to Banach spaces, in which $Df(x)(v)$ may be a clearer notation.