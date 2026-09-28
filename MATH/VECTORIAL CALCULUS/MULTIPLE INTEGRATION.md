# Double Integrals
Let $f$ be a function $f:\mathbb R^2\to\mathbb R$ defined on region $D$, where $D\subseteq\mathbb R^2$ and let a rectangle $P$ which contains the whole region $R$ where: 
$$P=[x_0,x_p]\times[y_0,y_q]\implies\Delta S_{i,j}=\Delta x_i\Delta y_j$$
Where $\Delta x_i$ is the length of the subinterval $[x_{i-1},\,x_i]$ and $\Delta y_j$ is the length of the subinterval $[y_{j-1},y_j]$. Let a partition $P$ with subareas that are inside of the region $R$  and $\Delta S_k=\Delta S_{i,j}$:
$$\lim_{\lVert P\rVert\to 0}\sum_{k=1}^n f(x_k^*,y_k^*)\,\Delta S_k=\iint_Df(x,y)\,\mathrm dS$$
Where $n$ is the total of subareas inside the region $D$ and $\lVert P\rVert$ is the greatest length or width of the partition $P$.
# Triple Integrals
Let a function $f:\mathbb R^3\to\mathbb R$ defined on a region $E$. where $E\subseteq\mathbb R^3$ and let a parallelepiped $P$ which contains the whole region $E$ where:
$$P=[x_0,x_p]\times[y_0,y_q]\times[z_0,z_r]\implies\Delta V_{i,j,k}=\Delta x_i\Delta y_j\Delta z_k$$
Where $\Delta x_i$ is the length of the subinterval $[x_{i-1},\,x_i]$, $\Delta y_j$ is the length of the subinterval $[y_{j-1},y_j]$. 
and $\Delta z_k$ is the length of the subinterval $[z_{k-1},z_k]$. Let a partition $P$ with subvolumes that are inside are inside of the region $E$ and $\Delta V_m=\Delta V_{i,j,k}$
$$\lim_{\lVert P\rVert\to0}\sum^n_{m=1}f(x^*_m,y^*_m,z^*_m)\,\Delta V_m=\iiint_Ef(x,y,z)\,\mathrm dV$$
Where n is the total of subvolumes inside the region $E$ and $\lVert P\rVert$ is the greatest length, width or height of the partition $P$.

---

# Fubini's Theorem
## For double integrals
Let a function $f:\mathbb R^2\to\mathbb R$ defined and continuous on a region $D$ and $D=\lbrace(x,y)\in\mathbb R^2\mid c\leq y\leq d\land g_1(y)\leq x\leq g_2(y)\rbrace$, then:
$$\iint_Df(x,y)\,\mathrm dA=\int^d_c\int^{g_2(y)}_{g_1(y)}f(x,y)\,\mathrm dx\,\mathrm dy$$
## For triple integrals
Let a function $f:\mathbb R^3\to\mathbb R$ defined and continuous on a region $E$ and$E=\lbrace(x,y,z)\in\mathbb R^3\mid(x,y)\in D\land u_1(x,y)\leq z\leq u_2(x,y)\rbrace$. Where $D=\lbrace(x,y)\in\mathbb R^2\mid c\leq y\leq d\land g_1(y)\leq x\leq g_2(y)\rbrace$.
$$\iiint_Ef(x,y,z)\,\mathrm dV=\iint_D\int^{u_2(x,y)}_{u_1(x,y)}f(x,y,z)\,\mathrm dz\,\mathrm dA$$

> The order of the variables $x,y$ and $z$ can be exchanged if it meets the conditions

---

# Change of Variables Theorem
## For double integrals
Let a function $f:\mathbb R^2\to\mathbb R$ defined and continuous on a region $D$, then:
$$\iint_Df(x,y)\,\mathrm dx\,\mathrm dy=\iint_Sf(g(u,v),h(u,v))\,|\det(J(u,v))|\,\mathrm du\,\mathrm dv$$
Where $S$ is the region $D$ expressed in the variables $u$ and $v$ and $J(u,v)$ is the jacobian matrix of the function $(x,y)=T(u,v)$:
$$\begin{equation}
J(u,v)=\frac{\partial(x,y)}{\partial(u,v)}=\begin{bmatrix}
\dfrac{\partial x}{\partial u} & \dfrac{\partial x}{\partial v} \\
\dfrac{\partial y}{\partial u} & \dfrac{\partial y}{\partial v}
\end{bmatrix}
\end{equation}
$$
## For triple integrals
Let a function $f:\mathbb R^3\to\mathbb R$ defined and continuous on a region $E$, then
$$\iiint_Ef(x,y,z)\,\mathrm dx\,\mathrm dy\,\mathrm dz=\iiint_Vf(g,h,k)\,|\det(J(u,v,w))|\,\mathrm du\,\mathrm dv\,\mathrm dw$$
Where $x=g(u,v,w),y=h(u,v,w),z=k(u,v,w)$, $V$ is the region $E$ expressed in the variables $u,v$ and $w$ and $J(u,v,w)$ is the jacobian matrix of the function $(x,y,z)=T(u,v,w)$:
$$\begin{equation}J(u,v,w)=\frac{\partial(x,y,z)}{\partial(u,v,w)} = \begin{bmatrix}
\dfrac{\partial x}{\partial u} & \dfrac{\partial x}{\partial v} & \dfrac{\partial x}{\partial w} \\[1em]
\dfrac{\partial y}{\partial u} & \dfrac{\partial y}{\partial v} & \dfrac{\partial y}{\partial w} \\[1em]
\dfrac{\partial z}{\partial u} & \dfrac{\partial z}{\partial v} & \dfrac{\partial z}{\partial w}
\end{bmatrix}
\end{equation}
$$
