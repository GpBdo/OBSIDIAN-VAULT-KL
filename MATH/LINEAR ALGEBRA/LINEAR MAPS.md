# Linear map (Linear transformation)
Let V and W vectorial spaces, then a linear map from $V$ to $W$  is a function $T:V\to W$ which meets:
- Additivity: $T(u+v)=Tu+Tv,\quad\forall u,v\in V$
- Homogeneity: $T(\lambda v)=\lambda(Tv),\quad\forall\lambda\in\mathbb F,\forall v\in V$
# Set of linear maps
The set of linear maps from $V$ to $W$ is $\mathcal L(V,W)$. The set of linear maps from $V$ to $V$ is $\mathcal L(V)$
## Addition and scalar multiplication on $\mathcal L(V,W)$
Let $S,T\in\mathcal L(V,W)$ and $\lambda\in F$, then:
$$\lbrace S+T,\lambda T\rbrace\in\mathcal L(V,W)$$
Where:
$$(S+T)(v)=Sv+Tv$$
$$(\lambda T)(v)=\lambda(Tv)$$
## Product of linear maps
Let $T\in\mathcal L(U,V)$ and $S\in\mathcal L(V,W)$, then the product $ST\in\mathcal L(U,W)$ is:
$$(ST)(u)=S(Tu),\quad\forall u\in U$$
Where the product of linear maps is a linear map composition $$ST=S\circ T$$
### Properties:
- **Associativity:** $(ST)P=S(TP)$
- **Identity:** $TI=IT=T$
- **Distributive:** $(S+T)P=ST+TP$ and $S(T+P)=ST+SP$.
> Each linear map of each property and subproperty has a right domain.
## Linear map lemma
Let $v_1,v_2,\ldots,v_n$ a basis of $V$ and $w_1,w_2,\ldots,w_n\in W$, then there exists only one linear map $T:V\to W$ such that:
$$Tv_k=w_k,\quad k=1,2,\ldots,n$$
---
# Range
Let a linear map $T\in\mathcal L(V,W)$, the range of $T$ is:
$$\text{range }T=\lbrace Tv\mid v\in V\rbrace$$
**Consequence:**
- $\text{range }T\subseteq W$
- $\text{range }T$ is a subspace of $W$
---
## Injective linear map
A linear map $T:V\to W$ is considered injective if :
$$Tu=Tv\iff u=v,\forall u,v\in V$$
## Surjective linear map
A linear map $T:V\to W$ is considered surjective if:
$$\text{range }T=W$$
