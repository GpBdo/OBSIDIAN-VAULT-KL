# THE MEAN VALUE OF A FUNCTION
If $f(x)$ is integrable on $[a,\,b]$, then the mean value on the interval $[a,\,b]$ is:
$$f_{avg}=\frac{1}{b-a}\int_a^bf(x)\,\mathrm{d}x$$
It indicates the average height determined by $f(x)$.
## Mean value theorem
If $f(x)$ is continuous on $[a,\,b]$:
$$\exists c\in [a,\,b]\Rightarrow f(c)=\frac{1}{b-a}\int_a^bf(x)\,\mathrm{d}x$$
---
# THE FUNDAMENTAL THEOREM OF CALCULUS
## Part I:
If $f$ is continuous over $[a,b]$ and $F(x)=\int_a^b f(t)\mathrm t$:
$$F'(x)=f(x)=\frac{\mathrm d}{\mathrm{d}x}\int^x_a f(t)\,\mathrm{d}t$$
### Proof:
- Using **Mean value Theorem** on the interval $[x,x+h]$:
$$\exists c\in[x,x+h]\Rightarrow f(c)=\frac{1}{h}\int^{x+h}_h f(t)\,\mathrm{d}t$$
- But:
$$\frac{1}{h}\int^{x+h}_x f(t)\,\mathrm{d}t=\frac{F(x+h)-F(x)}{h}$$
- Taking $h\to0$, then $\lim_{h\rightarrow 0}x+h=x$: 
$$\exists c\in[x,x]\Rightarrow f(x)=F'(x)$$
## Part II:
If $f$ is continuous over $[a,b]$ and $F$ is any antiderivative of $f$ on $[a,b]$, then:
$$\int^b_af(x)\,\mathrm{d}x=F(b)-F(a)$$
### Proof:
- Using  the **Part I of the Fundamental Theorem of Calculus** we got:
$$F(x)+C=\int^x_af(t)\,\mathrm{d}t$$
- Where $F$ is any antiderivative of $f$
$$(F(b)+C)-(F(a)+C)=F(b)-F(a)$$
$$F(b)-F(a)=\int^b_af(t)\,\mathrm{d}t-\int^a_af(t)dt=\int^b_af(t)\,\mathrm{d}t$$
