## Technical Details
###### Assumptions
$D$ is the [[Fréchet Derivative]]
$X,Y,Z$ are each a [[Banach Space]]
$U \subset X$,  $V \subset Y$ are both [[Open]]
$x \in U$
$f:U \to V$
$Df$ exists on all $U$
$g:V \to Z$
$Dg$ exists on all $V$
$h:U \to Z$ is defined by $h = g \circ f$
###### Conclusions
$h$ is differentiable on all $x$ and it satisfies the following:
$$
Dh(x) = Dg(f(x))Df(x)
$$
