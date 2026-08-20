**Definition**
Let a function $f:D\subseteq\mathbb{R}^n\to\mathbb{R}$ and a point $a\in D$. The function $f$ is differentiable at $a$ if:
$$\exists!\,T:\mathbb{R}^n\to\mathbb{R}\mid\lim_{\vec{v}\to\vec{0}}\dfrac{f(a+\vec{v})-f(a)-T(\vec{v})}{\lVert\vec{v}\rVert}=0$$
Where T is a linear transformation and the best linear approximation and is $\nabla f(a)\cdot\vec{v}$.
## Consequences
- The function $f$ is continuous at the point $a$.
- The function $f$ has its all partial derivatives at the point $a$.
### Proof of  $T(\vec{v})=\nabla f(a)\cdot\vec{v}$
- Any vector $\vec{v}\in\mathbb{R}^n$ can be built as $\vec{v}=\sum^n_{i=1}v_ie_i$, then:
$$T(\vec{v})=T\left(\sum^n_{i=1}v_i\,e_i\right)$$
- Using the definition of **Linear transformation**:
$$T(\vec{v})=\sum^n_{i=1}v_i\,T(e_i)\qquad(I)$$
- Replacing on differentiability definition $e_i$ in $\vec{v}$, we have:
$$\lim_{h\to0}\dfrac{f(a+he_i)-f(a)-T(he_i)}{|h|}=0$$
- Using the definition of **Linear transformation**:
$$\lim_{h\to0}\dfrac{f(a+he_i)-f(a)}{|h|}-T(e_i)=0$$
- Using the definition of **Partial derivative**:
$$\frac{\partial f}{\partial x_i}(a)=\lim_{h\to0}\dfrac{f(a+he_i)-f(a)}{|h|}=T(e_i)$$
- Replacing the result on the equation $(I)$ and using the definition of **Gradient**:
$$T(\vec{v})=\sum^n_{i=1}v_i\,\frac{\partial f}{\partial x_i}(a)=\nabla f(a)\cdot\vec{v}$$
$$\blacksquare$$


