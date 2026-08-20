# Linear Combination
The linear combination of some vectors $v_i\in V$ is:
$$a_1v_1+a_2v_2+\ldots+a_mv_m$$
Where $a_i\in\mathbb F$ 
## Span
Is the set of all linear combination of some vectors $v_i\in V$:
$$\mathrm{span}(v_1,v_2,\ldots,v_m)=\lbrace a_1v_1+a_2v_2+\ldots+a_mv_m\mid a_i\in\mathbb F\rbrace$$
### Finite-dimensional Vector Space
A vector space $V$ is finite-dimensional if it can be expressed as a span of some vectors
### Infinite-dimensional Vector Space
A vector space $V$ is infinite-dimensional if it isn't finite-dimensional

---
# Linearly Independent
Some vectors $v_i\in V$ are considered linearly independent if there is a only choice of coefficients $a_i\in\mathbb F$ to get other vector $(w)$ through  linear combination.
$$a_1v_1+a_2v_2+\ldots+a_mv_m=w$$
**Consequence:**
$$a_1v_1+a_2v_2+\ldots+a_mv_m=0\implies a_1=a_2=\ldots=a_m=0$$
# Linearly dependent
Some vector $v_i\in V$ are considered linearly dependent if they are not linearly independent.
## Linear dependence lemma:
Let some linear dependent vectors $v_i\in V$. Then:
$$\exists k\in\lbrace1,2,\ldots,m\rbrace\mid v_k\in\mathrm{span}(v_1,\ldots,v_{k-1},v_{k+1},\ldots)$$
