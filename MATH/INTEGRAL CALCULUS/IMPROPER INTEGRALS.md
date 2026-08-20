# Type 1 
Are integrals with infinite limit(s) of integration:
$$\int^\infty_af(x)\,\mathrm dx:=\lim_{t\to\infty}\int^t_af(x)\,\mathrm dx$$
$$\int^a_{-\infty}f(x)\,\mathrm dx:=\lim_{t\to-\infty}\int^a_tf(x)\,\mathrm dx$$
- If the limit exists and is a defined number, then the integral converges.
- If the limit doesn't exists or is infinite, then the integral diverges.
# Type 2
Are integrals whose function has discontinuities on the interval of integration:
$$\int^b_af(x)\,\mathrm dx,\quad f(x)\text{ is discontinuous at } x=c\text{ and } c\in[a,b]$$
If the discontinuity is at the integration limit, then:
- The upper limit $b$ is discontinuous on the function $f$:
$$\int^b_af(x)\,\mathrm dx=\lim_{t\to b^-}\int^t_af(x)\,\mathrm dx$$
- The lower limit $a$ is discontinuous on the function $f$:
$$\int^b_af(x)\,\mathrm dx=\lim_{t\to a^+}\int^b_tf(x)\,\mathrm dx$$
