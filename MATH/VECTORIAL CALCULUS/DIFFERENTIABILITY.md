**Definition**
Let a function $f:D\subseteq\mathbb R^n\to\mathbb R^m$ and a point $a\in D$. The function $f$ is differentiable at $a$ if:
$$\exists!\,T:\mathbb{R}^n\to\mathbb{R}\mid\lim_{\vec{v}\to\vec{0}}\dfrac{f(a+\vec{v})-f(a)-T\vec v}{\lVert\vec{v}\rVert}=0$$
Where T is a linear map, which is the best linear approximation and is the Jacobian Matrix $$\begin{equation}
J_f(x)=\begin{bmatrix}
\dfrac{\partial f_1}{\partial x_1} & \cdots & \dfrac{\partial f_1}{\partial x_n} \\
\vdots & \ddots & \vdots \\
\dfrac{\partial f_m}{\partial x_1}& \cdots & \dfrac{\partial f_m}{\partial x_n}
\end{bmatrix}
\end{equation}
$$
## Consequences
- The function $f$ is continuous at the point $a$.
- The function $f$ has its all partial derivatives at the point $a$.


