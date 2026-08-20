# General Clairaut-Schwarz Theorem
Let a function $f:\mathbb R^n\to\mathbb R$ and $f\in C^k(\mathbb R)$, then:
$$\dfrac{\partial^kf}{\partial x_{i_1}\partial x_{i_2}\ldots\partial x_{i_k}}=\dfrac{\partial^kf}{\partial x_{\sigma(i_1)}\partial x_{\sigma(i_2)}\ldots\partial x_{\sigma(i_k)}}$$
Where $n\ge2$, $k\ge2$ and $i_j \in\lbrace1,2,3,\ldots n\rbrace$. 
# Exact differential 
Let a function $f:\mathbb R^n\to\mathbb R$ and is differentiable at a point $a$. The exact differential of a function $f$ at the point $a$ is:
$$\mathrm df=\sum^n_{i=1}\frac{\partial f}{\partial x_i}(a)\,\mathrm dx_i $$
# Inexact differential
Let the differential expression and the function $M_i:\mathbb R^n\to\mathbb R$: 
$$\mathrm dQ=\sum^n_{i=1}M_i\,\mathrm dx_i$$
If there is no  function $f$, which $\mathrm df$ is $\mathrm dQ$, where $\dfrac{\partial f}{\partial x_i}=M_i$. Or if  the $M_i$ don't meet (By Clairaut Theorem)
$$\frac{\partial M_i}{\partial x_j}=\frac{\partial M_j}{\partial x_i},\quad\forall i,j\in\lbrace1,2,3,\ldots,n\rbrace\land i\neq j$$
The differential $\mathrm dQ$ is an inexact differential ($\delta Q$), otherwise $\mathrm dQ=\mathrm df$ is a exact differential.
