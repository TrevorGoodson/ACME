Section 11.1.2
This section assumes the IEEE 754 standard (64 bits to store a floating point number; 1 bit to store the sign, 11 to store the exponent, and 52 to store the significand, or fraction)
# Floating Point Number
A floating point, or non-integer real number, number is stored on a computer using two integers, $S$ and $e$, and a single bit for the sign. So, all floating point numbers take the form
$$
\pm\ S \cdot 2^e
$$
$S$ is a number between 1 and 2 ($10_2$), which stands for significand. The computer doesn't store $S$ directly, instead stores a large integer $s$, where $S = s \cdot 2^{-52}$ ($s$ has 53 digits, so $2^{-52}$ moves the leading digit to the ones space). Since $s$ will always have a leading 1, the computer saves space and stores every digit of $s$ except the leading one. So, the computer uses $52$ bits to store $s$, but we set the precision of $s$ (denoted $p$) to 53, the number of digits of $s$. Note $s$ is bounded by $b^{p-1} \le s < b^p$ since the leading digit must always be one.

$e$ is also not stored on the computer directly. Instead the computer stores an unsigned integer, $E$, where $e = E - 1023$. The intuition behind this comes from the fact that 11 bits can store integers up to 2047 ($2^{11} - 1$), and the "bias" of 1023 splits the possibilities equally between positive and negative. $E = 0$ ($e = -1023$) and $E = 2047$ ($e = 1024$) are reserved for representing special numbers (namely $\pm 0$, $\pm \infty$, and NaN--"not a number"). We set $M = 1022$, where $e = -M$ is the smallest it can be (excluding the special numbers). We set $N = 1023$, where $e = N$ is the largest it can be (again excluding the special numbers). A bias is used, rather than a separate sign for the bit, due to machine-level optimizations. 

We can generalize the expression even further if we set $b = 2$ (the base).

So, in order to analyze floating-point numbers, we construct a formal set, denoted $\mathbf F$.
Let $s, b, p, N, M \in \mathbb N$ and $e \in \mathbb Z$. $\mathbf F$ is defined by
$$
\mathbf F = \left\{\pm \frac{s}{b^{p-1}} b^e \ \middle | \ b^{p-1} \le s < b^p \text{ and} -M \le e \le N \right\} \cup \{ 0 \}
$$
---
# Axioms of Floating Point Arithmetic
## Machine Epsilon
###### Assumptions
$\epsilon_{\text{machine}} \in \mathbb R^+$
$x, \delta \in \mathbb R$
$b^{-M - 1} < x < b^{N + 1}$ (or the "representable range")
$\text{fl} : \mathbb R \to \mathbf F$ indicates conversion to a floating point number
###### Axiom
For any $x$, there exists $\delta$ such that $|\delta| \le \epsilon_{\text{machine}}$ and the following is satisfied
$$
\text{fl}(x) = (1 + \delta)x
$$
In other words,
$$
\frac{|\text{fl}(x) - x|}{|x|} \le \epsilon_{\text{machine}}
$$
$|\text{fl}(x) - x| / |x|$ is called the relative error.

## Standard Operations
###### Assumptions
$*$ is $+, -, \times$ or $/$
$\circledast$ is the floating point counterpart of of $*$
$x, y \in \mathbf F$
$\delta \in \mathbb R$
$|\delta| \le \epsilon_{\text{machine}}$
$x * y$ is in the representable range

###### Axiom
There exists $\delta$ such that
$$
x \circledast y = (1 + \delta)(x * y)
$$
In other words
   $$\left| \frac{(x \circledast y) - (x * y)}{x * y} \right| \le \epsilon_{\text{machine}}$$
The left hand expression is called the relative error