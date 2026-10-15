#Definition Definition 11.3.5
## Intuition
Any numeric implementation of a function using [[Floating-Point Number]]s introduces error. The backward error is a way to quantify that error.
Call the original function $f$ and the numeric implementation $\tilde f$. The desired input is $x$.
The backwards error is the distance between the $x$ and the closest value (lets call it $x'$) such that $\tilde f(x) = f(x')$.
If you think of the actual error of $\tilde f$ as occurring in the compute process, the backward error is a way to simulate that error as an error in the input.

## Technical Details
###### Assumptions
$\| \cdot \|$ is the [[Norm]] on $\mathbb F^n$
$x, \delta \in \mathbb F^n$
$f: \mathbb F^n \to \mathbb F^m$
$\tilde f$ is a numeric implementation of $f$
$\text{min}$ is the [[Minimum]]
###### Definition
The absolute backward error of $\tilde f$ at $x$, denoted $\widehat{\beta}_{\tilde f}$ , is defined as
$$
\widehat{\beta}_{\tilde f} = \text{min} \{ \| \delta \| : \tilde f(x) = f(x + \delta)\}
$$
The relative backward error of $\tilde f$ at $x$, denoted $\beta_{\tilde f}$, is defined as
$$
\beta_{\tilde f} = \frac{\widehat{\beta}_{\tilde f}}{\|x\|}
$$
## Key Results
