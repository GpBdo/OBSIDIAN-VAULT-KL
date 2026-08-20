# Vectorial space $(V)$
A vector space over a field $\mathbb F$ is a non-empty set of elements called vectors $({v})$ with two operations (sum, scalar multiplication) that satisfies:
- **Vector addition axioms**
	- Associativity: $(u+v)+w=u+(v+w),\quad\forall u,v,w\in V$
	- Commutativity: $u+v=v+u,\quad\forall u,v\in V$
	- Additive identity: $\exists 0\in V\mid\forall v\in V, v+0=v$
	- Additive inverse: $\forall v\in V\exists(-v)\in V\mid v+(-v)=0$
- **Scalar multiplication axioms**
	- Distributivity (vector addition): $k(v+u)=kv+ku,\quad\forall k\in\mathbb F,\forall u,v\in V$
	- Distributivity (scalar addition): $(a+b)v=av+bv,\quad\forall a,b\in\mathbb F,\forall v\in V$
	- Compatibility: $a(bv)=(ab)v,\forall a,b\in\mathbb F,\forall v\in V$
	- Identity: $\exists 1\in\mathbb F,\forall v\in V\mid 1v=v$
## Subspaces of a vector space
Is a subset of a vector space $V$ that is itself a vector space (Satisfies the 8 axioms)
### Sum of subspaces
Let $V_1,V_2,\ldots,V_m$ subspaces of a vector space $V$, then the sum of subspaces is:
$$V_1+V_2+\ldots+V_m =\lbrace v_1+v_2+\ldots+{v}_m\mid v_k \in V_k,\quad k=1,2,\ldots,m\rbrace$$
**Consequence:**
- $V_1+V_2+\ldots+V_m\subseteq V$
### Direct sum $(\oplus)$
If and only if the following condition is satisfies by a subspaces of a vector space $V$:
$$V_i\,\cap\,\sum_{j\neq i}V_j=\lbrace\vec{0}\rbrace$$
Then:
$$V_1+V_2+\ldots+V_m =V_1\oplus V_2\oplus \ldots\oplus V_m$$
Where $\oplus$ indicates there is only one possible sum of vector that creates one element of the sum vector set.