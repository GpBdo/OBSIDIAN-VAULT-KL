# Trabajo mecánico $(W)$
Cuantifica la energía transferida por una fuerza $\vec F$ a un cuerpo, contribuyendo al cambio de su energía cinética a lo largo de una trayectoria. 
El trabajo infinitesimal de una fuerza resultante $\vec F$ a lo largo de un desplazamiento infinitesimal es:
$$\delta W=\vec F\cdot\mathrm d\vec r$$
El trabajo de una fuerza $\vec F$ a lo largo de una trayectoria $C$ es:
$$W=\int_C \vec F\cdot\mathrm d\vec r$$
---
$$\delta W=m\frac{\mathrm d\vec v}{\mathrm dt}\cdot\mathrm d\vec r=m\vec v\,\mathrm d\vec v$$
$$\delta W=\mathrm d\left(\frac{mv^2}{2}\right)$$
## Energía cinética $(K)$
Cuantifica el movimiento de un cuerpo con masa $m$ y una rapidez $v$, el cual es generado por el trabajo mecánico de una fuerza desde el reposo hasta dicha rapidez.
$$K=\frac{1}{2}mv^2$$
Obtenemos de $\delta W$ para una fuerza resultante a un cuerpo:
$$\delta W=\mathrm dK$$
### Teorema Trabajo-Energía
El trabajo neto aplicado por una cantidad de fuerzas a un cuerpo es el cambio de su energía cinética
$$W_{neto}=\Delta K$$
# Fuerza conservativa
Se define como fuerza conservativa a una fuerza cuyo trabajo mecánico solo depende de la posición inicial y final, no de la trayectoria entre dichas posiciones.
El trabajo realizado por una fuerza conservativa $\vec F_{cons}$ de un punto A hacia un punto B es:
$$W=\int^B_A\vec{F}_{cons}\cdot\mathrm d\vec r$$
---
Se escoge un punto arbitrario $P$ por donde pasa la trayectoria del cuerpo:
$$W=\int^B_P\vec{F}_{cons}\cdot\mathrm d\vec r+\int^P_A\vec{F}_{cons}\cdot\mathrm d\vec r$$
$$W=-\int^A_P\vec{F}_{cons}\cdot\mathrm d\vec r+\int^B_P\vec{F}_{cons}\cdot\mathrm d\vec r$$
## Energía potencial
Cuantifica el trabajo mecánico por una fuerza conservativa cuando mueve un cuerpo de un punto $Q$ hacia un punto de referencia $P$. 
$$U(Q)=\int^P_Q\vec F_{cons}\cdot\mathrm d\vec r=-\int^Q_P\vec F_{cons}\cdot\mathrm d\vec r$$
Donde $U(P)=0$ de manera arbitraria y por conveniencia.
> La energía acumulada en el punto $Q$ es la que usará la fuerza conservativa en el movimiento de dicho punto $Q$ a punto $P$ de referencia. Esto nos indica que el trabajo de la fuerza conservativa se almacena en energía potencial 

Del trabajo de una fuerza conservativa obtenemos que:
$$W=U(A)-U(B)=-\Delta U$$
---
$$\delta W=-\mathrm dU$$
Pero:
$$\mathrm dU=\frac{\partial U}{\partial x}\mathrm dx+\frac{\partial U}{\partial y}\mathrm dy+\frac{\partial U}{\partial z}\mathrm dz=\nabla U\cdot\mathrm d\vec r$$
Entonces:
$$\vec F\cdot\mathrm d\vec r=-\nabla U\cdot\mathrm d\vec r\implies\vec F=-\nabla U$$
# Fuerza no conservativa
Se define como fuerza no conservativa a una fuerza cuyo trabajo mecánico depende de la trayectoria recorrida del cuerpo. 
> El trabajo mecánico de una fuerza no conservativa no se almacena en energía potencial, sino se transforma en otra forma de energía.

## Energía mecánica
Cuantifica una cantidad abstracta y el trabajo mecánico que puede realizar un cuerpo sobre sí mismo u otro cuerpo.
$$E_m=K+U$$
$$W_{nc}=\Delta E_m$$
---
