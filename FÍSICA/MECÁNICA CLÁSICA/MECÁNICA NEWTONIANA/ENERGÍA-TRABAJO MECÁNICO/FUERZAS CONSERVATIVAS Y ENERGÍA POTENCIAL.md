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

