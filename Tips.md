Common notation used for the sum of terms (Greek S) ($\Sigma$)

> [!note] 
> - Sigma Notation in LaTeX is `\sum_{lower}^{upper}` 
> - Fraction in LaTeX is `\frac{num}{den}`

In general, instead of writing $u_1 + u_2 + u_3 + ... + u_n$, we write
$$\sum_{i=1}^{n}u_i = u_1 + u_2 + u_3 + ... + u_n$$
- $n$ = upper value for $i$
- $u_1$ = general term written in terms of $i$
- $i=1$ = initial value for $i$

> [!question] 
>  **Expand and simplify the following.**
>  $$\sum_{k=0}^{8}(k-3)^3$$
>  $= (0-3)^3 + (1-3)^3 + (2-3)^3 + ... + (8-3)^3$
>  $= (-3)^3 + (-2)^3 + (-1)^3 + (0)^3 + ... + (5)^3$
>  $= (4)^3 + (5)^3$
>  $= 189$

> [!tip] 
> **Sigma Notation in the TI-Nspire CX CAS II**
> 1. Press *menu* button
> 2. Press 4 or go to the *Calculus* section
> 3. Press 3 or press *Sum* button

## Properties of $\Sigma$

1. $\Sigma$ is distributive. That is, $\sum_{i=1}^{n}[u_i + v_i] = \sum_{i=1}^{n}u_i + \sum_{i=1}^{n}v_i$
2. $\sum_{i=1}^{n}ku_i = k\sum_{i=1}^{n}u_i$, for some constant value $k$.
3. $\sum_{i=1}^{n}k = kn$, i.e., adding a constant term, $k$, $n$ times is the same as multiplying $k$ by $n$.

> [!info] 
> Another helpful formula is: $$1+2+3+4+...+ n = \sum_{i=1}^{n}i = \frac{n(n+1)}{2}$$

> [!question] 
> Solve the following using the above properties. Check your answer by expanding the summation and adding: $$\sum_{i=1}^{8}(3-2i)$$
> 1. $= \sum_{i=1}^{8}3 - \sum_{i=1}^{8}2i$
> 2. $= 3(8) - 2\sum_{i=1}^{8}i$
> 3. $= 24 - 2\frac{8(8+1)}{2}$
> 4. $= 24-72$
> 5. $= -48$ 