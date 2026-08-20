## Vector tangente unitario $(\hat{T})$
Indica la dirección de la velocidad instantánea. 
$$\hat{T}=\frac{\mathrm{d}\vec{r}}{\mathrm{d}s}=\frac{\vec{v}}{\lVert\vec{v}\rVert}$$
## Vector normal unitario $(\hat{N})$
Indica hacia que dirección está cambiando la velocidad instantánea.
$$\hat{N}=\frac{\dfrac{\mathrm{d}\hat{T}}{\mathrm{d}s}}{\left\lVert\dfrac{\mathrm{d}\hat{T}}{\mathrm{d}s}\right\rVert}$$
## Vector binormal unitario $(\hat{B})$
Indica un plano que contiene la mayor cantidad de puntos de una trayectoria muy cerca de un punto definido en un instante.
$$\hat{B}=\hat{T}\times\hat{N}$$
### Ecuaciones diferenciales de Frenet-Serret
Los vectores unitarios del triedro de Frenet-Serret satisfacen el siguiente sistema de ecuaciones diferenciales:
$$\begin{cases}
\dfrac{\mathrm{d}\hat{T}}{\mathrm{d}s}=\kappa\hat{N}\\
\dfrac{\mathrm{d}\hat{N}}{\mathrm{d}s}=-\kappa\hat{T}-\tau\hat{B}\\
\dfrac{\mathrm{d}\hat{B}}{\mathrm{d}s}=-\tau\hat{N}
\end{cases}$$
**Donde:**
- $\kappa$: Curvatura 
- $\tau$: Torsión
### Radio de curvatura
Indica el radio de la circunferencia que contiene la mayor cantidad de puntos de una trayectoria muy cerca de un punto definido en un instante.
$$\frac{1}{\rho}=\kappa=\left\lVert\frac{\mathrm{d}\hat{T}}{\mathrm{d}s}\right\rVert$$
# Vector de Darboux $(\vec\omega)$ 
Indica el eje de rotación y rapidez con la que rota el triedro de Frenet-Serret en conjunto.
$$\vec\omega=\tau\hat T+\kappa\hat B$$
