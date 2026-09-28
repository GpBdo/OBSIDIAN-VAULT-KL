Let $u_i$ be the $i$-th coordinate of a coordinate system, then the vector position is:
$$\vec r=x\hat i+y\hat j+z\hat k$$
where:
$$x=x(u_1,u_2,u_3),\quad y=y(u_1,u_2,u_3),\quad z=z(u_1,u_2,u_3)$$
---
# Unit basis vector
Let $\hat e_i$ be a unit vector pointing in the direction of increasing $u_i$, with the other coordinates held fixed:
$$\hat e_i=\dfrac{\dfrac{\partial\vec r}{\partial u_i}}{\left\lVert\dfrac{\partial\vec r}{\partial u_i}\right\rVert}$$
and the unit basis vectors are orthogonal each other:
$$\hat e_i\cdot\hat e_j=\delta_{ij}$$
# Scale factor
The scale factor $h_i$ is the scale of the change of the coordinate $u_i$ to convert to a change of the distance in the coordinate system.
$$\mathrm ds_i=h_i\,\mathrm du_i$$
where $h_i$ is:
$$h_i=\left\lVert\dfrac{\partial\vec r}{\partial u_i}\right\rVert$$
## Differential of the position 
The total change of the position is the sum of scaled changes of the coordinates.
$$\mathrm d\vec x=\sum^3_{i=1}h_i\,\mathrm du_i\,\hat e_i$$
---
# Differential operators
## Gradient
Let $\phi$ be a function $\phi:\mathbb R^3\to\mathbb R$ and $\phi=\phi(u_1,u_2,u_3)$, then the gradient of $\phi$ is:
$$\nabla\phi=\sum^3_{i=1}\frac{1}{h_i}\frac{\partial\phi}{\partial u_i}\hat e_i$$
## Divergence
Let $F$ be a function $F:\mathbb R^3\to\mathbb R^3$ and $\vec F=F_1\hat e_1+F_2\hat e_2+F_3\hat e_3$
$$\nabla\cdot\vec F=\frac{1}{h_1h_2h_3}\left[\frac{\partial}{\partial u_1}(h_2h_3\,F_1)+\frac{\partial}{\partial u_2}(h_1h_3\,F_2)+\frac{\partial}{\partial u_3}(h_1h_2\,F_3)\right]$$
