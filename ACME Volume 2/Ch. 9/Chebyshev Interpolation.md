# Monic Chebyshev Polynomials
#Definition Section 9.3.2
## Intuition

## Technical Details
###### Assumptions

###### Definition
$$
\widehat T_0 = 1\ ;\ \widehat T_1(x) = x\ ;\ \widehat T_2(x) = x^2 - \frac 12\ ;\cdots ; \widehat T_{n}(x) = x \widehat T_{n-1}(x) - \frac 14 \widehat T_{n-2}(x) \text{ for } n \ge 3
$$

## Key Results

---
# Chebyshev Polynomials
#Definition Section 9.3.3
## Intuition

## Technical Details
###### Assumptions

###### Definition
$$
T_0 = 1\ ;\ T_1(x) = x\ ;\ T_2(x) = 2x^2 - 1\ ;\cdots ; T_{n}(x) = 2xT_{n-1}(x) - T_{n-2}(x) \text{ for } n \ge 3
$$

## Key Results
- $T_n(\cos(t)) = \cos(nt)$ (Remark 9.3.2)
- The chebyshev polynomials form an [[Orthonormal]] basis for the set of polynomials

---
# Chebyshev Zeros and Extremizers
#Theorem Proposition 9.3.3
## Intuition

## Technical Details
###### Assumptions

###### Conclusions
zeros:
$$
z_j = \cos \left(\frac{\pi}{n} \left(j + \frac 12 \right)\right)
$$
extremizers:
$$
y_j = \cos \left( \frac{j\pi}{n} \right)
$$
## Key Results
- The chebyshev extremizers minimizes the [[Nodal Polynomial]], and thus the [[Interpolation Error]] (Follows from Theorem 9.4.4)
