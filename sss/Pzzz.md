$$\int^5_0\frac{1}{x\sqrt{25-x^2}}\,\mathrm dx$$
$$\int\frac{e^{32x}}{(e^{8x}+1)^3}$$
$$\frac{\mathrm d}{\mathrm du}\int^u_0t^3+a\,\mathrm dt$$

$$\mathrm\delta W=\vec F\cdot\mathrm d\vec r$$

$$l=\frac{v_o\sqrt M}{\sqrt{bMg+K}}$$

$$\begin{bmatrix}
6\\
2\\
3
\end{bmatrix}$$
```tikz
\begin{document}

\begin{tikzpicture}[scale=1.5]

% --------------------------------
% Ejes
% --------------------------------

\draw[->,very thick] (0,0) -- (0,6);
\draw[->,very thick] (0,0) -- (7.5,0);

\node[scale=1.5] at (-0.3,5.8) {$y$};
\node[scale=1.5] at (7.3,-0.35) {$x$};

% --------------------------------
% Vectores unitarios i y j
% --------------------------------

\draw[->,ultra thick] (0,0) -- (0.85,0);
\node[scale=1.5] at (0.45,-0.35) {$\hat{i}$};

\draw[->,ultra thick] (0,0) -- (0,0.85);
\node[scale=1.5] at (-0.35,0.45) {$\hat{j}$};

% --------------------------------
% Vector radial r
% --------------------------------

\draw[->,ultra thick] (0,0) -- (4.25,3.05);

\node[scale=1.6] at (2.35,2) {$r$};

% --------------------------------
% Vector unitario radial
% --------------------------------

\draw[->,ultra thick] (4.25,3.05) -- (5.25,3.75);

\node[scale=1.5] at (5.25,4.05) {$\hat{r}$};

% --------------------------------
% Vector unitario theta
% --------------------------------

\draw[->,ultra thick] (4.25,3.05) -- (3.55,4.00);

\node[scale=1.5] at (3.55,4.35) {$\hat{\theta}$};

% --------------------------------
% Circunferencia
% --------------------------------

\draw[thick,dashed]
    (0,{sqrt(4.25*4.25 + 3.05*3.05)})
    arc (90:0:{sqrt(4.25*4.25 + 3.05*3.05)});

% --------------------------------
% Angulo theta
% --------------------------------

\draw[ultra thick]
    (1.55,0)
    arc (0:35.7:1.55);

\node[scale=1.5] at (1.9,0.6) {$\theta$};

% --------------------------------
% Punto de referencia
% --------------------------------

\fill (4.25,3.05) circle (0.07);

\end{tikzpicture}

\end{document}
```

---
Ich mag Physik
Heute lerne ich Berechnung
Ich lerne Physik, weil die Formeln interessant sind
Ich mag Mathematik, aber die Gleichungen sind kompliziert.
Ich kann die Aufgabe verstehen.
ich weiß, dass Mathematik kompliziert ist
Ich will Physik lernen, weil ich Physik mag und ich Physiker werden will.
Ich habe die Doppelintegrale gelernt $\iint$
Wie definierst du die Doppelintegrale?
Ich habe die Kinematik gelernt, weil sie grundlegend ist.
Ich kann lineare Algebra verstehen
Wer war Max Planck?
Max Planck hat den Nobelpreis im Jahr 1918 gewonnen.
Ich kann das Problem mit dem Satz von Stokes lösen.
Ich lerne deutsch, während ich Softwaretechnik lerne.
Ich habe das Problem analysiert.
Die Lösung für das Problem ist kompliziert.
Sei $f$ eine reelle $(\mathbb R)$ Funktion

---
$$A\cup(B-C)$$
$$x\in A\lor(x\in B\land x\notin C)$$
$$(x\in A\lor x\in B)\land (x\in A\lor x\notin C)$$
$$(x\in A\lor x\in B)\land \sim(x\notin A\land x\in C)$$
$$(A\cup B)-(C-A)$$
---
Aprobaré Matemática discreta, si Dios quiere. Aprobaré Matemática discreta si y sólo si
estudio y hago todos los ejercicios. Sin embargo, no he hecho los ejercicios, asi que Dios
no quiere que apruebe Matemática discreta. **Escribir la expresión lógica.**
$$(q\to p)\land[p\iff (r\land s)]\land[\sim s\to\sim q] $$
Los investigadores de la universidad Cayetano, evaluaron los resultados de una vacuna a
un grupo de cientos de pobladores del cono norte de Lima, con resultados favorables,
entonces podríamos concluir que la vacuna es válida para toda la población limeña,
justifique su respuesta.
- No se puede pasar de un conjunto particular (Cono norte de Lima) a un conjunto universo (Lima) sin más evidencias 
Realizar en pseudocódigo el algoritmo de una secuencia de números leídos por teclado, que
acabe con un -1, por ejemplo: 4,3,0,5,6,2,0,0,5,4,7,0,.......-1; Realizar el algoritmo que
calcule la media aritmética. Suponemos que el usuario no insertará número negativos.
```
Inicio
	Definir suma, contador, numero, media como reales;
	suma ← 0;
	contador ← 0;
	Escribir "Ingrese su numero: ";
	Leer numero;
	Mientras (numero != -1)
		suma ← suma + numero;
		contador ← contador + 1;
		
		Escribir "Ingrese su numero: ";
		Leer numero;
	FinMientras
	Media ← (suma/contador);
	Escribir Media;
Fin
```
---
1.- Formule la expresión simbólica con palabras utilizando:
$$[p\lor(\sim q\land\sim(q\lor r))]\to(q\lor\sim(r\lor q))$$
p: Hoy es lunes
q: esta lloviendo
r. hace frio
$$[\sim(q\lor(q\lor r))\lor p]\to(q\lor\sim(r\lor q))$$
$$[(r\lor q)\to p]\to(q\lor\sim r)$$
2.- Demostrar:
a) $(A-B)\cup(B-A)=(A\cup B)-(A\cap B)$
$$(x\in A\land x\notin B)\lor(x\in B\land x\notin A)$$
$$[(x\in A\land x\notin B)\lor x\in B]\land[(x\in A\land x\notin B)\lor x\notin A]$$
$$(x\in A\lor x\in B)\land(x\notin B\lor x\notin A)$$
$$(x\in A\lor x\in B)\land\sim(x\in B\land x\in A)$$
$$(A\cup B)-(A\cap B)$$
b) $X\subseteq Y\iff Y'\subseteq X'$
$$x\in X\to x\in Y$$
$$x\notin Y\to x\notin X$$
—"So easy btw"
3.- Escriba un algoritmo en pseudocódigo cuya salida sean los elementos de la sucesión ordenados en forma descendente
$$S_1,S_2\ldots,S_{n-1},S_n$$
4.- Una familia está compuesta por tres miembros, hallar la función lógica que permita
decidir si se ve o no una película de acción en la casa, sabiendo que, en el caso de que
los dos padres estén de acuerdo, esa será la decisión a tomar,
Solo en caso de no estar de acuerdo los padres la decisión lo tomará la hija. Se pide,
a) La expresión lógica que expresa la solución óptima al problema de ver la pelicula de
acción.
Sea 
p: Decisión del padre
q: Decisión de la madre
r: Desición de la hija
$$(p\underline{\lor}q)=\text{Decision final}$$
b) La expresión minima y el circuito lógico mediante lógica de interruptores
$$r\lor(p\underline q)$$
$$R_{\mu\nu}-(1/2)g_{\mu\nu}R+\frac{1}{\tilde{Ñ}}T_{\mu\nu}=0$$
$$\begin{align*}
\text{Usamos la relación de la cinemática: } a &= v \frac{dv}{ds} \\
v \frac{dv}{ds} &= - \frac{g R_E^2}{s^2} \\
\int_{v_0}^{0} v \, dv &= - g R_E^2 \int_{s_0}^{h} \frac{1}{s^2} \, ds \\
\left[ \frac{1}{2}v^2 \right]_{v_0}^{0} &= - g R_E^2 \left[ -\frac{1}{s} \right]_{s_0}^{h} \\
0 - \frac{1}{2}v_0^2 &= g R_E^2 \left( \frac{1}{h} - \frac{1}{s_0} \right) \\
\frac{1}{2}v_0^2 &= g R_E^2 \left( \frac{1}{s_0} - \frac{1}{h} \right) \\
v_0 &= \sqrt{2gR_E^2 \left( \frac{1}{s_0} - \frac{1}{h} \right)}
\end{align*}
$$
$$\int^{\pi/4}_{-\pi/4}\frac{x\sin x}{\sqrt[x] e+1}dx$$
$$\sqrt 2\int\frac{u^2\sqrt{1+u^2}}{1-u^4}du$$
