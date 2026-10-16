#Definition 
## Intuition

## Technical Details
###### Assumptions

###### Definition
An algorithm is stable if $\delta_x, C, D$ exist such to satisfy
$$
\frac{\| \delta_x \|}{\| x \|} \le C \epsilon_{\text{machine}}
$$
and 
$$
\frac{\| f(x+\delta_x) - \tilde f(x) \|}{\| f(x+\delta_x) \|} \le D \epsilon_{\text{machine}}
$$
## Key Results
- if the [[Relative Condition Number]] of $f$ is [[Bounded]] and $f$ is [[Backward Stable]], then $f$ is stable (Theorem 11.3.16)
- stability does NOT imply backwards stability
