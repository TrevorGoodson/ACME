#Definition Definition 3.5.10

## Technical Details
###### Assumptions
$(V, \|\cdot\|_V), (W, \|\cdot\|_W)$ are normed spaces
$\sup$ is the [[Supremum]]
$T:V \to W$
$x \in V$
###### Definitions
The set of bounded linear transformations, denoted $\mathscr B(V;W)$, is defined by the set of [[Linearity|linear]] maps where the following quantity is [[Bounded|bounded]]:
$$
\| T \|_{V,W} = \sup_{x \ne 0} \frac{\|T(x)\|_W}{\|x\|_V} = \sup_{\|x\|_V = 1} \|T(x)\|_W
$$
$\| \cdot \|_{V,W}$  is called the induced norm on $\mathscr B(V;W)$. **Important:** unless otherwise stated in context, the induced norm is THE norm on bounded linear transformations.

## Key Results
- ($\mathscr B(V;W), \| \cdot \|_{V,W})$ is indeed a [[Norm|normed]] [[Linearity|linear]] space (Theorem 3.5.11)