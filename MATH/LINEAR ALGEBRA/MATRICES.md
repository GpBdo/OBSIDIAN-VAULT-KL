Let an unitary ring $\mathcal R$, then a matrix $A_{m\times n}$ is a function $A:\lbrace1,\ldots,m\rbrace\times\lbrace1,\ldots,n\rbrace\to\mathcal R$, where $m,n\in\mathbb Z^+$ and the element $A(i,j)=(A)_{ij}\in \mathcal R$, which graphic representation is:
$$\begin{equation}
A=
\begin{bmatrix}
A_{1,1}&\cdots&A_{1,n}\\
\vdots&\ddots&\vdots\\
A_{m,1}&\cdots&A_{m,n}
\end{bmatrix}
\end{equation}$$
# Operation with matrices
## Addition
Let the matrices $A_{m\times n}$ and $B_{m\times n}$, then the sum of the matrices is:
$$C=A+B$$
Where $C$ is the matrix $C_{m\times n}$ and $(C)_{ij}=(A)_{ij}+(B)_{ij}$.
## Scalar multiplication
Let the matrix $A_{m\times n}$ and a escalar $\lambda\in\mathbb F$, then the scalar multiplication of the matrix is:
$$B=\lambda A$$
Where $B$ is the matrix $B_{m\times n}$ and $(B)_{ij}=\lambda(A)_{ij}$.
## Product
Let the matrices $A_{m\times n}$ and $B_{n\times p}$ , then the product of the matrices is:
$$C=AB$$
Where $C$ is the matrix $C_{m\times p}$ and each element is:
$$(C)_{ij}=\sum^n_{k=0}(A)_{ik}(B)_{kj}$$
---
# Other matrices
## Transpose of a matrix
Let the matrix $A_{m\times n}$, then its transpose is $A^T$ and $(A^T)_{ij}=(A)_{ji}$
**Consequences:**
- $(AB)^T=B^TA^T$ 
## Identity matrix
Let the matrix $I_{n\times n}=I_n$, then is called identity if:
$$(I)_{ij}=\begin{cases}1&\text{if } i=j\\
0&\text{if }i\neq j
\end{cases}$$
## Symmetric matrix
Let the matrix $A_{n\times m}$, then is called symmetric if:
$$A=A^T$$
## Skew-symmetric matrix
Let the matrix $A_{n\times m}$, then is called skew-symmetric if:
$$-A=A^T$$
---
# Inverse matrix
 Let the matrix $A_{n\times n}$, then the inverse matrix $A^{-1}$ and the matrix meets:
$$AA^{-1}=A^{-1}A=I$$
 **Consequences:**
 - The inverse matrix of a matrix es unique.
 - $(AB)^{-1}=B^{-1}A^{-1}$ 
 - $(A^T)^{-1}=(A^{-1})^T$
# More matrices...
## Orthogonal matrix
Let a matrix $A_{n\times n}$, then is called orthogonal if $AA^T=I\implies A^{-1}=A^T$ . 