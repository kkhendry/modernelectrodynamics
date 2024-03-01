## Problem 2.1 ##

Using Coulomb's Law 
> $F = q(v \times B)$

and taking 

> $v \times F$ 

$= q[v \times (v \times B)]$

Applying the triple cross product rule $A \times B \times C = B(A \cdot C) + C(A \cdot B)$

$= q[v (v \cdot B) + B(v \cdot v)]$

Rearranging, we can derive an expression for B in terms of $v_1$ and $v_2$:

$B|v|^2 = v(v \cdot B) - \frac{v \times F}{q}$

$B = \frac{1}{|v_1|^2} [v_1(v_1 \cdot B) - \frac{v_1 \times F}{q}]$

$B = \frac{1}{|v_2|^2} [v_2(v_2 \cdot B) - \frac{v_2 \times F}{q}]$

Our expression for $B$ includes $v\cdot B$, we can resolve this by deriving an expression for $v \cdot B$ which does not include $B$:

$v_1 \cdot B = \frac{1}{|v_2|^2} [(v_1 \cdot v_2)(v_2 \cdot B) - v_1 \cdot \frac{v_2 \times F}{q}]$

If $v_1 \perp v_2$ then $v_1 \cdot v_2 = 0 \rightarrow v_1 \cdot B = -v_1 \cdot \frac{v_2 \times F}{q|v_2|^2}$

$\rightarrow B = -\frac{1}{q} [\frac{1}{|v_1|^2}(v_1 \times F) + \frac{1}{|v_2|^2}(v_2 \times F)]$

and so, the expression we derive for B in terms of $v \times F$ and $v$ shows that if $v_1$ and $v_2$ are orthogonal, then B is simply the negative sum of the respective $v_i \times F$ weighted by the magnitude of the square of $v_i$ and divided by $q$

Generalizing, for orthogonal $v_i$:

$B = -\frac{1}{q} \sum_i{\frac{1}{|v_i|^2}(v_i \times F)}$











 
