# Line integrals
## For scalar fields
Let a function $f:\mathbb R^n\to\mathbb R$ continuous over a curve $C$, then the line integral of $f$ over a curve $C$ is:
$$\int_Cf(x_1,x_2,\ldots,x_n)\,\mathrm ds=\lim_{\lVert P\rVert\to0}\sum^n_{k=1}f(x_{1_k},x_{2_k},\ldots,x_{n_k})\Delta s_k$$
Where $C$ is a curve parametrically by $\vec r(t)= (y_1(t),y_2(t),\dots,y_n(t))$, $t\in[a,b]$ and $P$ is the partition of $\vec r$. By change of variable theorem:
$$\int_Cf(x_1,x_2,\ldots,x_n)\,\mathrm ds=\int^b_af(y_1(t),y_2(t),\dots,y_n(t))\lVert\vec r'\rVert\,\mathrm dt$$
## For vector fields
Let a function $F:\mathbb R^n\to\mathbb R^n$ continuous over a curve $C$, then the line integral of $\vec F$ over a curve $C$ is:
$$\int_C\vec F\cdot\mathrm d\vec r=\lim_{\lVert P\rVert\to0}\sum^n_{k=1}\vec F(x_{1_k},x_{2_k},\ldots,x_{n_k})\cdot\Delta\vec r_k$$
Where $C$ is a curve parametrically by $\vec r(t)= (y_1(t),y_2(t),\dots,y_n(t))$, $t\in[a,b]$ and $P$ is the partition of $\vec r$. By change of variable theorem:
$$\int_C\vec F\cdot\mathrm d\vec r=\int^b_a\vec F\cdot\vec r'\,\mathrm dt$$
# Flow integrals
Let a function $F:\mathbb R^n\to\mathbb R^n$ and continuous over a curve $C$, then the flow along the curve from point $A$ to $B$ is:
$$\mathrm{flow}=\int_C\vec F\cdot\hat T\,\mathrm ds$$
Where if $A$ and $B$ are the same point ($A=B$), the flow is called circulation around the curve $C$. 
# Flux integrals
## For simple closed curves
Let a function $F:\mathbb R^2\to\mathbb R^2$ continuous on a simple close curve $C$, then the flux of $F$ across $C$ is:
$$\Phi_C=\oint_C\vec F\cdot\hat n\,\mathrm ds$$
Where $\hat n=\hat T\times\hat B$ 
## For simple surfaces
Let a function $F:\mathbb R^3\to\mathbb R^3$ , then the flux of the vectorial field over a surface $S$ is:
$$\Phi=\iint_S\vec F\cdot\mathrm d\vec S$$
**Interpretation:**
Indicates how much quantity of a vector field goes throughout a determined surface $S$. 

---
# Fundamental theorem of line integrals
Let $f$ be a function $f:\mathbb R^n\to\mathbb R$ and let $C$ be a curve that goes from the point $A$ to point $B$ then:
$$\int_C\nabla f\cdot\mathrm d\vec r=f(B)-f(A)$$