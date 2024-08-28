## Aufgabe 1

Es seien die folgenden gegeben:

$$a_n = \frac {n^2-3n+1}{2n}-\frac n 2$$
$$f(x)=\frac{x^4-2x^2+3x-2}{2x^3-x^2-1}$$
a) Bestimmen wir den Grenzwert:

$$\lim_{n \rightarrow \infty} a_n$$
$$=\lim_{n \rightarrow \infty} \frac {n^2-3n+1}{2n}-\frac n 2$$
$$=\lim_{n \rightarrow \infty}  \frac {n^2-3n+1}{2n}-\frac {n^2} {2n}$$
$$=\lim_{n \rightarrow \infty} \frac {n^2-3n+1- n^2}{2n}$$
$$=\lim_{n \rightarrow \infty} \frac {-3n+1}{2n}$$
$$= \lim_{n \rightarrow \infty} \frac{n(-3+\frac 1 n)}{n\cdot2}$$
$$= \lim_{n \rightarrow \infty} \frac{-3+\frac 1 n}{2} = -\frac 3 2$$

b) Bestimmen wir den Grenzwert:

$$\lim_{x \rightarrow 2} f(x)$$
$$=f(2)$$
$$= \frac{2^4-2\cdot2^2+3\cdot2-2}{2\cdot2^3-2^2-1}$$
$$=\frac{16-8+6-2}{2^4-4-1}$$
$$=\frac{16-8+6-2}{16-4-1}$$
$$=\frac{8+4}{12-1}$$
$$=\frac{12}{11}$$

c) Bestimmen wir den Grenzwert:

$$\lim_{x \rightarrow 1} f(x)$$
$$=\lim_{x \rightarrow 1} \frac{x^4-2x^2+3x-2}{2x^3-x^2-1}$$
Da hier der Grenzwert $\frac 0 0$ wäre, nutzen wir den Satz von L'Hôpital:
$$= \lim_{x \rightarrow 1} \frac{4x^3-4x+3}{6x^2-2x}$$
$$=\frac{4\cdot(1)^3 - 4\cdot1 + 3}{6\cdot(1)^2 - 2\cdot1}$$
$$=\frac{4-4+3}{6-2}$$
$$=\frac 3 4$$

## Aufgabe 2

a) Gegeben ist die folgende Reihe:
$$\sum_{k=1}^{\infty} \frac{(-4)^k}{3^k}$$
Bestimmen wir dessen Konvergenzverhalten anhand des Quotientenkriteriums:

$$q=\lim_{n \rightarrow \infty} \lvert \frac{a_{n+1}}{a_n} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{(\frac 4 3)^{n+1}}{(\frac 4 3)^n} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert (\frac 4 3)^{n+1} \cdot \frac 1 {(\frac 4 3)^n} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert (\frac 4 3)^n \cdot (\frac 4 3) \cdot \frac 1 {(\frac 4 3)^n} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert (\frac 4 3) \rvert = \frac 4 3$$

Da $q = \frac 4 3$ größer als 1 ist, divergiert die Reihe.


b) Gegeben ist die folgende Reihe:
$$\sum_{k=1}^{\infty} \frac{n^2-7}{2^n}$$
Prüfen wir dessen Konvergenzverhalten anhand des Quotientenkriteriums:

Sei $a_n = \frac {n^2-7}{2^n}$:

$$q = \lim_{n \rightarrow \infty} \lvert \frac{a_{n+1}}{a_n} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{{\frac{(n+1)^2-7}{2^{n+1}}}} {\frac{n^2-7}{2^{n}}}\rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)^2-7}{2^{n+1}} \cdot \frac{2^{n}}{n^2-7} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{n^2+2n+1-7}{2^n\cdot2} \cdot \frac{2^{n}}{n^2-7} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{n^2+2n+1-7}{2} \cdot \frac{1}{n^2-7}\rvert$$
$$= \lim_{n \rightarrow \infty} \lvert \frac{n^2+2n-6}{2(n^2-7)} \rvert$$
$$= \lim_{n \rightarrow \infty} \lvert \frac{n^2+2n-6}{2n^2-14} \rvert$$
$$= \lim_{n \rightarrow \infty} \lvert \frac{n^2(1+\frac 2 n- \frac 6 {n^2})}{n^2(2-\frac {14}{n^2})} \rvert$$
$$= \lim_{n \rightarrow \infty} \lvert \frac{1+\frac 2 n- \frac 6 {n^2}}{2-\frac {14}{n^2}} \rvert = \frac 1 2$$

Da $q=\frac 1 2$ kleiner als 1 ist, konvergiert die Reihe.

c) Gegeben ist die Reihe:
$$\sum_{k=1}^{\infty} \frac{k!}{k^k}$$
Bestimmen wir das Kovergenzverhalten anhand des Quotientenkriteriums:

Sei $a_n = \frac{n!}{n^n}$:

$$q = \lim_{n \rightarrow \infty} \lvert \frac{a_{n+1}}{a_n} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{\frac{(n+1)!}{(n+1)^{n+1}}} {\frac{n!}{n^n}} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)!}{(n+1)^{n+1}} \frac{n^n}{n!}\rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{n!(n+1)}{(n+1)^{n+1}} \cdot \frac{n^n}{n!}\rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)}{(n+1)^{n+1}} \cdot {n^n}\rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{{n^n}(n+1)}{(n+1)^{n+1}} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{{n^n}(n+1)}{(n+1)^n(n+1)} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{{n^n}}{(n+1)^n} \rvert$$
$$=\lim_{n \rightarrow \infty} (\frac{{n}}{(n+1)})^n$$

Hier nutzen wir die uns gegebene Bedingung: $\lim_{k \rightarrow \infty} (\frac k {(k+1)})^k = \frac 1 e$:
$$=\frac 1 e$$
## Aufgabe 3

a) Wir bilden die erste Abbildung der Funktion:

$$f(x)=(5x-3)^{10}$$
$$f'(x)=10(5x-3)^9\cdot5 = 50(5x-3)^9$$
b) Wir bilden die erste Abbildung der Funktion:

$$g(x)=\sqrt{1-3x} \cdot \sin(x)$$
$$=(1-3x)^{\frac 1 2}\cdot \sin(x)$$
$$g'(x)=\frac 3 2(1-3x)^{-\frac 1 2}\cdot\sin(x)+(1-3x)^{\frac 1 2}\cdot\cos(x)$$


c) Wir bilden die erste Abbildung der Funktion:

$$h(x)=\frac{\sin(x)}{\cos(x)}$$
$$h'(x)=\frac{\cos(x)\cos(x)-\sin(x)(-\sin(x))}{\cos^2(x)}$$
$$=\frac{\cos^2(x)+\sin^2(x)}{\cos^2(x)}$$

## Aufgabe 4

Gegeben sei die Funktion: $f(x)=\sin^2(x)$.

a) Um zu zeigen, dass $$f'''(x)=-4\cdot f'(x)\ \land f^{(5)}(x)=16\cdot f'(x)$$
Bilden wir die Ableitungen von $f$:

$$f'(x)=2(\sin(x))\cos(x) = 2\sin(x)\cos(x)$$
$$f''(x)=2\cos(x)\cos(x)+2\sin(x)(-\sin(x))$$
$$=2\cos^2(x)-2\sin^2(x)$$
$$f'''(x)=4(\cos(x)(-\sin(x)))-4(\sin(x))\cos(x)$$
$$f^{(4)}(x)=-8(\cos(x))^2+8(\sin(x))^2$$
$$f^{(5)}(x)=16(2\sin(x)\cos(x))$$
$$=16f'(x)$$


b) Bestimmen wir nun anhand der Ableitungen das Taylorpolynom $T_4(x)$:

$$T_4(x)=\sum_{k=0}^4 \frac{f^(k)(0)}{k!}(x-0)^k$$
$$=\frac{\sin^2(0)}{0!}x^0+\frac{2\sin(0)\cos(0)}{1!}x+\frac{2\cos^2(0)-2\sin^2(0)}{2!}x^2-\frac{8\sin(0)\cos(0)}{3!}x^3-\frac{8\cos^2(0)+8\sin^2(0)}{4!}x^4$$
$$=0x^0+0x+\frac{2\cdot1^2-0}{2!}x^2-0x^3-\frac{8\cos(0)}{4!}x^4$$
$$=\frac 2 2 x^2 - \frac 8 {24} x^4$$
$$=x^2-\frac 1 3x^4$$

c) Um den Fehler zu ermitteln nutzen wir folgende Formel:

$$\lvert f(x) - T_4(x) \rvert$$
$$=\lvert R_4(x)\rvert$$
$$=\lvert \frac{f^{(5)}(\alpha)}{5!} \cdot x^5 \rvert$$
$$=\frac 1 {5!} \lvert f^{(5)}(\alpha) \cdot x^5 \rvert$$
$$=\frac 1 {5!} \lvert 32\sin(\alpha)\cos(\alpha)x^5\rvert$$
$$=\frac 1 {5!} \lvert 32x^5 \rvert$$
$$= \frac 1 {5!} \lvert 32 (\frac 1 2)^5 \rvert$$
$$= \frac 1 {5!} \cdot 32 \cdot \frac 1 {32}$$
$$=\frac 1 {5!} = \frac 1 {120}$$
## Aufgabe 5

a) Es soll die Stammfunktion für folgende Funktion gebildet:
$$f(x)=x^2\cdot e^x$$

$$\int x^2\cdot e^x dx$$
$$=x^2\cdot e^x - \int 2x\cdot e^x dx$$
$$=x^2\cdot e^x - (2xe^x - \int 2e^x dx)$$
$$=x^2\cdot e^x - (2xe^x - 2\int e^x dx)$$
$$=x^2\cdot e^x - (2xe^x - 2 e^x )$$
$$F(x)=e^x(x^2-2x-2)$$
b)Gegeben ist die Funktion: 
$$f(x)=-x^2+3x+4$$
Um die Fläche von $f$ innerhalb des 2.Quadranten zu bestimmen, müssen wir dessen negative Nullstellen bestimmen, da diese als Integrationsgrenze dient:

$$-x^2 + 3x + 4 = 0 \vert \cdot (-1)$$
$$\Leftrightarrow x^2-3x-4 = 0 \vert +4$$
$$\Leftrightarrow x^2 - 3x + (\frac 3 2)^2= 4 + (\frac 3 2)^2$$
$$\Leftrightarrow (x-\frac 3 2)^2 = \frac{16}4 + \frac 9 4$$
$$\Leftrightarrow (x-\frac 3 2)^2 = \frac {25}{4} \vert \sqrt{}$$
$$\Leftrightarrow x-\frac 3 2 = \frac 5 2 \vert + \frac 3 2 \ \lor x-\frac 3 2 = -\frac 5 2 \vert + \frac 3 2$$
$$\Leftrightarrow x = \frac 8 2 \ \lor x = \frac {-2}2$$
$$\Leftrightarrow x = 4 \ \lor \ x = -1$$

Wir betrachten also:

$$\int_{-1}^0 -x^2+3x+4 dx$$
$$=-1 \cdot \int_{-1}^0 x^2-3x-4 dx$$
$$=-1 \cdot [\frac 1 3 x^3 - \frac 3 2 x^2 - 4x]$$
$$=-1(-(\frac 1 3 (-1)^3 - \frac 3 2(-1)^2 - 4\cdot(-1)))$$
$$=-1(-1(-\frac 1 3 + \frac 3 2 + 4))$$
$$=-1(\frac 1 3 - \frac 3 2 - 4)$$
$$=-\frac 1 3 + \frac 3 2 + 4$$
$$=-\frac 2 6 + \frac 9 6 + \frac {24}6$$
$$=\frac 7 6 + \frac {24}6$$
$$=\frac {31} 6$$

