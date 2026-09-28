Let a function $F:\mathbb R^n\to\mathbb R^n$ be defined on an open region $D$ and let two points $A,B\in D$. If:
$$\int_{C_1}\vec F\cdot\mathrm d\vec r=\int_{C_2}\vec F\cdot\mathrm d\vec r$$
for all curves $C_1,C_2\subset D$ that go from $A$ to $B$, then the function $\vec F$ is conservative in the region $D$ and the integral is path independent. 

## Potential function
Let a function $F:\mathbb R^n\to\mathbb R^n$  be defined on an open region $D$. If:
$$\exists f\mid\vec F=\nabla f$$
then the function $\vec F$ is conservative in the region $D$ and the function $f$ is called potential function of $\vec F$.
# The fundamental theorem of line integrals
Let  $F:\mathbb R^n\to\mathbb R^n$ be a conservative function in a region $D$ and let $f$ be a potential function of $\vec F$, then:
$$\int_C\vec F\cdot\mathrm d\vec r=\int_C\nabla f\cdot\mathrm d\vec r=f(B)-f(A)$$
Where $C\subset D$ is a curve that goes from $A$ to $B$.
