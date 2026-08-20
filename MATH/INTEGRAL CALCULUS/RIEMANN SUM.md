x# PARTITION
A partition is a finite set of points that divides a closed interval into subintervals.
$$P=\{x_0,\,x_1,\,x_2,\,x_3,\,...,\,x_n\}$$
Where the number of subintervals is $n$:
$$[x_0,\,x_1],\,[x_1,\,x_2],\,[x_2,\,x_3],\,..[x_{n-1},\,x_n]$$
## Norm of a partition $(\lVert P\rVert)$
The norm of the partition P is the longest length of all the subintervals.
$$\lVert P\rVert=\mathrm{max}(\Delta x_1,\,\Delta x_2,\,\Delta x_3,\,...,\,\Delta x_n)$$
Where $\Delta x_i$ is the length of the subinterval $[x_{i-1},\,x_i]$.
# RIEMANN SUM
Let the function $f(x)$ is defined on the close interval $[a,\,b]$ and the partition $P=\{x_1,\,x_2,\,x_3,\,...,\,x_n\}$ of $[a,\,b]$. The area $A$ under the a curve on a function $f(x)$ graph is:
$$A=\sum_{i=1}^{n}f(c_i)\,\Delta x_i$$
Where $c_i$ is a sample point of the subinterval $[x_{k-1},x_k]$.

---
# DEFINITE INTEGRAL DEFINITION
The definite integral is the limit of the Riemann sum of a function when $\lVert P\rVert\to0$.
$$I=\lim_{\lVert P\rVert\to0}\sum^n_{k=1}f(c_k)\,\Delta x_k=\int^b_a f(x)\,\mathrm{d}x$$
Where $c_k$ is any point of the subinterval $[x_{k-1},\,x_k]$ and $n$ is the number of subintervals. 
**Consequences:**
- If $f(x)$ is continuous in $[a,\,b]$, then $f(x)$ is integrable on $[a,\,b]$.
- If the value of the limit $I$ depends on the choice of $c_k$, then $f(x)$ is not integrable.
## Properties of the definite integrals
- Order of integration:
$$\int^b_af(x)\,\mathrm{d}x=-\int^a_bf(x)\,\mathrm{d}x$$
- Zero width interval: $\Delta x_k=0$
$$\int^a_af(x)\,\mathrm{d}x=0$$
- Max-min inequality: $x\in[a,\,b]$ 
$$\min(f(x))\cdot(b-a)\le\int^b_af(x)\,\mathrm{d}x\le\max(f(x))\cdot(b-a)$$
- Sum and difference:
$$\int^b_af(x)\pm g(x)\,\mathrm{d}x=\int^b_a f(x)\,\mathrm{d}x\,\pm\int^b_ag(x)\,\mathrm{d}x$$
- Domination:
$$f(x)\ge g(x),\qquad\forall x\in[a,\,b]\Rightarrow\int_a^bf(x)\,\mathrm{d}x\ge\int_a^bg(x)\,\mathrm{d}x$$