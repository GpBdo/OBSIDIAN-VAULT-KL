## Ordered pair
A set of 2 elements where the order matters and is defined (*Kuratowski*):
$$(a,b):=\lbrace\lbrace a\rbrace,\lbrace a,b\rbrace\rbrace$$
## Tuple
A ordered list of elements, defined by ordered pair:
$$(a_1,a_2,\ldots,a_n)=((a_1,a_2,\ldots,a_{n-1}),a_n)$$
# Cartesian product
Is an operation of 2 sets that creates a new set that have all possible ordered pairs created by the elements of the sets.
Let $A$ and $B$ sets, then their cartesian product is:
$$A\times B = \lbrace (a,b)\mid a\in A, b\in B\rbrace$$
## Relation $(R)$
$$R=\lbrace (a,b)\in A\times B\mid p(a,b)\rbrace\implies R\subseteq A\times B$$
### Domain 
$$\text{Dom}(R)=\{a\in A\mid \exists b\in B,(a,b)\in R\}$$
### Range
$$\text{Ran}(R)=\{b\in B\mid \exists a\in A,(a,b)\in R\}$$
## Function $(f)$
A relation $f \subseteq A\times B$ is a function $f:A\rightarrow B$ if it satisfies the condition:
$$\forall a\in A, \exists!b\in B\mid (a,b)\in f$$
---
# Field $(\mathbb{F})$
Is a set with two operations $(+, \times)$ and satisfies:
- **Addition axioms**
	- Closure: $a,b\in\mathbb F\implies a+b\in\mathbb F$
	- Associativity: $(a+b)+c=a+(b+c)\quad\forall a,b,c\in\mathbb F$
	- Commutativity: $a+b=b+a\quad\forall a,b\in\mathbb F$
	- Additive identity: $\exists0\in\mathbb F\mid\forall\in\mathbb F,a+0=a$
	- Additive inverse: $\forall a\in\mathbb F,\exists(-a)\mid a+(-a)=0$
- **Multiplication axioms**
	- Closure: $a,b\in\mathbb F\implies a\times b\in\mathbb F$
	- Associativity: $(a\times b)\times c=a\times(b\times c),\quad\forall a,b,c\in\mathbb F$
	- Commutativity: $a\times b=b\times a,\quad\forall a,b\in\mathbb F$
	- Multiplicative identity: $\exists 1\in\mathbb F\setminus\lbrace0\rbrace\mid\forall a\in\mathbb F,a\times1=a$
	- Multiplicative inverse: $\forall a\in\mathbb F\setminus\lbrace0\rbrace,\exists a^{-1}\in\mathbb F\mid a\times a^{-1}=1$
- **Distributive Law**
	- Distributivity: $a\times(b+c)=(a\times b)+(a\times c),\quad\forall a,b,c\in\mathbb F$
## Formal definition of the set $\mathbb{F}^S$
Let a set $S$ and a field $\mathbb{F}$ then:
$$\mathbb{F}^S:=\lbrace f\mid f: S\rightarrow \mathbb{F}\rbrace$$
**Consequence:**
- $\mathbb{F}^S\subseteq \mathcal{P}(S\times\mathbb{F})$
