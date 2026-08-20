**Definition**
Let a function $f:D\subseteq\mathbb{R}^n\to\mathbb{R}$, then the gradient of the function $f$ is:
$$\mathrm{grad}(f)=\nabla f(x_1,x_2,\ldots,x_n)=\left(\frac{\partial f}{\partial x_1},\frac{\partial f}{\partial x_2},\ldots,\frac{\partial f}{\partial x_n}\right)$$
**Interpretation**
The gradient of the function $f$ at a point $a$ is a vector pointing in the direction of maximum increase of the function near $a$.

---

## Directional Derivative Theorem
Let a differentiable function $f:D\subseteq\mathbb{R}^n\to\mathbb{R}$, then:
$$D_\vec{u}f(a)=\nabla f(a)\cdot\vec{u}$$
### Proof:
- By the definition of **Differentiability**:
$$\lim_{\vec{v}\to\vec{0}}\dfrac{f(a+\vec{v})-f(a)-\nabla f(a)\cdot\vec{v}}{\lVert\vec{v}\rVert}=0$$
- Let $\vec{v}=h\vec{u}$, where $\lVert\vec{u}\rVert=1$, then:
$$\lim_{h\to0}\dfrac{f(a+h\vec{u})-f(a)-\nabla f(a)\cdot h\vec{u}}{|h|}=0$$
- Using the definition of **Directional Derivative**:
$$D_\vec{u}f(a)=\lim_{h\to0}\dfrac{f(a+h\vec{u})-f(a)}{|h|}=\nabla f(a)\cdot \vec{u}$$
$$\blacksquare$$
