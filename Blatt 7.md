## Aufgabe 1

a) Gegeben ist die folgende Funktion:

$$f: \mathbb{R} \rightarrow \mathbb{R}, f(x)=\sin(x)$$
Das Taylorpolynom $T_7(x)$ ist gegeben mit Entwicklungspunkt $x_0=0$.

Das Taylorpolynom ist:
$$T_n(x)=\sum_{k=0}^n \frac{-1^k}{(2k+1)!}$$

Das Restglied für $T_7(x)$ ist:

$$R_7(x)=\frac{(-1)^4}{(2\cdot4+1)!}\ x^{(2\cdot4+1)}$$
$$= \frac 1 {9!}x^9$$
Die obere Schranke für $\alpha \in [0,\frac{\pi}2]$:
$$R_7(\frac{\pi}{2})=\frac 1 {9!} (\frac{\pi}2)^9$$

b) Folgende Ungleichung soll gelöst werden:

$$\lvert f(x)-T_7(x)\rvert < 0.001$$
**Einschub**:
Wir wissen:
$$f(x) = T_n(x) + R_n(x)\ \vert - T_n(x)$$
$$\Leftrightarrow f(x)-T_n(x) = R_n(x)$$
Substituieren wir in unsere Ungleichung:

$$\lvert R_n(x) \rvert < 0.001$$
$$\Leftrightarrow \lvert \frac{f^{(n+1)}(x)}{(n+1)!}\rvert < 0.001$$
$$\Leftrightarrow \frac 1 {(n+1)!}  \lvert f^{(n+1)}(x) \cdot x^{n+1}\rvert < 0.001$$

Da wir wissen, dass $f(x)=sin(x)$ und dessen Ableitungen Funktionswerte zwischen -1 und 1 besitzt können wir folgende Umformung machen:

$$\Leftrightarrow \frac 1 {(n+1)!} x^{n+1} < 0.001$$
$$\Leftrightarrow \frac {x^{n+1}}{(n+1)!} < 0.001$$

Hier kriegen wir durch Ausprobieren aus, dass die Ungleichung für $n = 7$ gilt.
## Aufgabe 2
Dies ist der Graph:

![[./assets/Pasted image 20240826201011.png]]
Die Fläche im Intervall $[-1, 1]$ beträgt:

$$\int_{-1}^0 e^{2x} dx - \int_0^1 e^{-x} dx$$
$$=[\frac 1 2e^{2x}]_{-1}^0\ -\ [-1e^{-x}]_0^1$$
$$=\frac 1 2 [e^{2x}]_{-1}^0\ -\ [-e^{-x}]_0^1$$
$$=\frac 1 2 (e^0 - e^2) - (-e^{-1} + e^0)$$
$$=\frac 1 2(1-e^2) - (-\frac 1 e + 1)$$

## Aufgabe 3

a) Lösen wir folgendes Integral:

$$\int xe^{3x} dx$$
Hierbei nutzen wir partielle Integration mit
$$f(x)=x \land g(x)=e^{3x}$$
$$\Rightarrow x \cdot \frac 1 3 e^{3x} - \int \frac 1 3 e^{3x}$$
$$= x\cdot \frac 1 3 e^{3x}-\frac 1 3 \int e^{3x}$$
$$=x\cdot\frac 1 3 e^{3x}-\frac 1 3(\frac 1 3 e^{3x})$$
$$=\frac 1 3 e^{3x} (x-\frac 1 3)$$

b) Lösen wir folgendes Integral: 

$$\int x^2\cos(x^3+4)dx$$
Formen wir das Integral wie folgt um:

$$\frac 1 3 \int 3x^2\cdot\cos(x^3+4) dx$$
$$=\frac 1 3 \sin(x³+4)$$
c) Zu lösen ist das folgende Integral:

$$\int \cos(2x)(\sin(2x))^4 dx$$
$$=\frac 1 2 \int 2\cos(2x)(\sin(2x))^4 dx$$

Hier haben wir das Schema $\int g'(x) f(g(x)) dx$ mit $g(x)=\sin(2x)$ und dementsprechend nutzen wir das Substitutionsschema:

Sei $u = \sin(2x)$:

$$\frac 1 2 \int u^4 du$$
$$= \frac 1 2 \cdot \frac 1 5 u^5$$
$$=\frac 1 {10} u^5$$

Tun wir $u$ nun rücksubstituieren:

$$\Rightarrow \frac 1 {10} (\sin(2x))^5$$


d) Gegeben ist folgendes Integral:

$$\int_{-1}^{1} \frac{e^x-e^{-x}}{e^x+e^{-x}} dx$$
Hier haben wir das Schema:

$$\int \frac {f'(x)}{f(x)} dx$$
Dementsprechend wird das Integral wie folgt berechnet:

$$[\ln(\lvert e^x+e^{-x})\rvert]_{-1}^1$$
$$=\ln(\lvert e^1+e^{-1}\rvert ) - \ln(\lvert e^{-1}+e¹\rvert )$$

e) Zu lösen ist folgendes Integral:

$$\int_0^1 (2x+3)^{20} dx$$
$$=\frac 1 2 \int_0^1 2(2x+3)^{20} dx$$
Hier haben wir das Schema $$\int_0^1 f(g(x))\cdot g'(x) dx$$ mit $g(x) = 2x+3$. Dementsprechend nutzen wir das Substitutionsprinzip:

Sei $u = 2x+3$:

$$\frac 1 2 \int_{g(0)}^{g(1)} u^{20} du$$
$$=\frac 1 2 \int_3^5 u^{20} du$$
$$=\frac 1 2 [\frac 1 {21} u^{21}]_3^5$$
$$=\frac 1 2 \cdot \frac 1 {21} [u^{21}]_3^5$$
$$=\frac 1 {42} [u^{21}]_3^5$$
$$=\frac 1 {42} (3^5 - 3^3)$$
## Aufgabe 4

a) Gegeben ist die Taylorreihe von $e$ mit Entwicklungspunkt $x_0 = 0$:

$$e = \sum_{k=0}^{\infty} \frac {x^k}{k!} = \sum_{k=0}^{\infty} \frac 1 {k!} (x-0)^k$$

Geben wir nun anhand dieser Reihe, die Taylorreihe für $e^{-x^2}$ an:

$$e^{-x^2} = \sum_{k=0}^{\infty} \frac 1 {k!}(-x^2-0)^k$$
$$=\sum_{k=0}^{\infty} \frac 1 {k!}(-x²)^k$$
$$=\sum_{k=0}^{\infty} \frac {(-x^2)^k}{k!}$$

Somit ist also unsere Taylorreihe $T_n$ für $e^{-x^2}$:

$$T_n(x)= \sum_{k=0}^n \frac {(-x^2)^k}{k!}$$

b) Berechnen wir nun anhand dieser Reihe, das Polynom $T_6(x)$:

$$T_6(x)= \sum_{k=0}^6 \frac {(-x^2)^k}{k!}$$$$=\frac{(-x^2)^0}{0!} + \frac{-x^2}{1!} + \frac{(-x^2)^2}{2!}+\frac{(-x^2)^3}{3!}+\frac{(-x^2)^4}{4!}+\frac{(-x^2)^5}{5!}+\frac{(-x^2)^6}{6!}$$
$$=1-x^2+\frac{x^4}{2!}-\frac{x^6}{3!}+\frac{x^8}{4!}-\frac{x^{10}}{5!}+\frac{x^{12}}{6!}$$

$$T_6(x)=1-x^2+\frac{x^4}2-\frac{x^6}6+\frac{x^8}{24}-\frac{x^{10}}{120}+\frac{x^{12}}{720}$$

Berechnen wir nun $\int_0^1 T_6(x) dx$:

$$\int_0^1 T_6(x) dx$$
$$=\int_0^1 1-x^2+\frac{x^4}2-\frac{x^6}6+\frac{x^8}{24}-\frac{x^{10}}{120}+\frac{x^{12}}{720}$$
$$=\int_0^1 1- \int_0^1 x^2+ \int_0^1 \frac{x^4}2-\int_0^1 \frac{x^6}6+ \int_0^1 \frac{x^8}{24}- \int_0^1 \frac{x^{10}}{120}+ \int_0^1 \frac{x^{12}}{720}$$
$$=\int_0^1 1- \int_0^1 x^2+ \frac 1 2 \int_0^1 x^4 - \frac1 6 \int_0^1 x^6 + \frac1{24} \int_0^1 x^8- \frac1{120} \int_0^1 x^{10} + \frac1{720} \int_0^1 x^{12}$$
$$=[x]_0^1 - [\frac 1 3 x^3]_0^1 + \frac 1 2 [\frac 1 5 x^5]_0^1-\frac 1 6[\frac 1 7 x^7]_0^1+\frac 1{24}[\frac 1 9 x^9]_0^1-\frac 1 {120}[\frac 1 {11} x^{11}]_0^1+\frac 1 {120}[\frac 1 {13} x^{13}]$$
$$=1 - \frac 1 3 + \frac 1 {10} - \frac 1 {42} + \frac 1 {216} - \frac 1 {1320} + \frac 1 {9360} \approx 0.75$$

Vergleichen wir den Näherungswert $\int_0^1 T_6(x) dx$ mit $\int_0^1 e^{-x^2} dx$ durch Erechnen des Verhältnisses beider Integrale:

$$\frac {\int_0^1 e^{-x^2} dx}{\int_0^1 T_6(x) dx} \approx 0.99$$

Joa...nd schlecht würd ich mal sagen, nh?