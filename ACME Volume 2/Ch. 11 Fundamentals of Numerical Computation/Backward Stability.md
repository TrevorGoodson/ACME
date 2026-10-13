## Intuition
A function is backwards stable if the error of the function is limited by machine precision
You can view the error in $\tilde f$ as only an error in what $\tilde f$ thinks the input is, then $\tilde f$ maps that input correctly. $x + \delta$ can be seen as the simulated error of $\tilde f$. If the distance between the input and the simpulated input

## Technical Details
###### Assumptions
$f$ is some function on $\mathbb F^n$
$\tilde f$ is an algorithm for $f$
$C \in \mathbb R^+$
$\epsilon _{\text{machine}}$ is the [[Floating-Point Number|machine epsilon]]
$\delta \in \mathbb F^n$ with $\tilde f(x) = f(x + \delta)$
###### Definition
$\tilde f$ is defined as backward stable if $\delta$ exists such that
$$
\frac{\| \delta \|}{\| x \|} \le C \epsilon_{\text{machine}}
$$
