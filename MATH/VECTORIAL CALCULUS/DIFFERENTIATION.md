# Limits
Let a function $f:D\subseteq\mathbb{R}^n\to\mathbb{R}^m$ then:
$$\begin{align*}
\lim_{x\to c}f(x)=L \iff &\forall\epsilon\in\mathbb{R},\epsilon>0,\exists\delta\in\mathbb{R},\delta>0\mid\forall x\in D,\\
&0<\lVert x-c\rVert<\delta\rightarrow\lVert f(x)-L\rVert<\epsilon
\end{align*}$$
## Continuity
Let a function $f:D\subseteq\mathbb{R}^n\to\mathbb{R}^m$. So:
$$f\text{ is continuous on }c\iff c\in D \,\land \lim_{x\to c}f(x)=f(c)$$
# Partial Derivatives
Let a function $f:D\subseteq\mathbb{R}^n\to\mathbb{R}^m$ continuous on $a$, then:
$$D_{x_i}f(a)= \frac{\partial f}{\partial x_i}(a)=\lim_{h\to0}\frac{f(a+he_i)-f(a)}{h}$$
# Directional Derivatives
Let a function $f:D\subseteq\mathbb{R}^n\to\mathbb{R}^m$ continuous on $a$, then:
$$D_{\vec{u}}f(a)=\lim_{h\to0}\frac{f(a+h\vec{u})-f(a)}{h}$$
Where:  $\lVert\vec{u}\rVert=1$
