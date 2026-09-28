Se usa una base de vectores unitarios ortogonales entre sí, pero son variables:
$$\hat r=\cos\theta\,\hat i+\sin\theta\,\hat j$$
$$\hat\theta=-\sin\theta\,\hat i+\cos\theta\,\hat j$$
# Posición
$$\vec r=r\cdot\hat r$$
**Consecuencias geométricas:**
- $\mathrm d\hat r=\mathrm d\theta\,\hat\theta$
- $\mathrm d\hat\theta =-\mathrm d\theta\,\hat r$ (Se pone un "$-$" por la dirección del cambio)
# Velocidad
$$\mathrm d\vec r=\mathrm dr\,\hat r+r\mathrm d\theta\,\hat\theta\implies\vec v=\dot r\,\hat r+r\dot\theta\,\hat\theta=\vec v_r+\vec v_t$$
**Donde:**
- $\mathrm dr\,\hat r$ indica el cambio radial de la posición. (Velocidad radial)
- $r\mathrm d\theta\,\hat\theta$ indica el cambio tangencial de la posición. (Velocidad tangencial)
# Aceleración
$$\vec a=(\ddot r-r{\dot\theta}^2)\,\hat r+(r\ddot\theta+2\dot r\dot\theta)\,\hat\theta$$
## Aceleración radial $((\ddot r-r{\dot\theta}^2)\,\hat r)$
- $\ddot r$ indica el cambio de la rapidez del cambio radial respecto al tiempo.
- $-r\dot\theta^2$ indica el cambio de la rapidez del cambio de dirección respecto al tiempo. Se usa "$r$" para expresar dicho efecto. (Se pone un "$-$" por la dirección del cambio).
## Aceleración angular $((r\ddot\theta+2\dot r\dot\theta)\,\hat\theta)$
- $r\ddot\theta$ indica el cambio de la dirección de la velocidad tangencial.
- $2\dot r\dot\theta$ indica la aceleración coriolis.
