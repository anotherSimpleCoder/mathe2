## Aufgabe 1

a) Gegeben sind:
$$a_n = \frac {2n}{n+10}, \epsilon = 10^{-3}, g = 2$$

Zu bestimmen ist $n < N_{\epsilon}$:

$$\lvert a_n - g\rvert < \epsilon$$
$$\Leftrightarrow \lvert \frac{2n}{n+10} - 2\rvert < 10^{-3}$$
$$\Leftrightarrow \lvert \frac{2n}{n+10} - \frac{2(n+10)}{n+10} \rvert < 10^{-3}$$
$$\Leftrightarrow \lvert \frac{2n-2(n+10)}{n+10} \rvert < 10^{-3}$$

$$\Leftrightarrow \lvert \frac{2n - 2n - 20}{n+10} \rvert < 10^{-3} $$
$$\Leftrightarrow \lvert \frac{-20}{n+10} \rvert < 10^{-3}$$
$$\Leftrightarrow \frac{20}{n+10} < 10^{-3} \vert \cdot (n+10)$$
$$\Leftrightarrow 20 < 10^{-3}(n+10)$$
$$\Leftrightarrow 20 < 10^{-3}n + 10^{-2}\vert-10^{-2}$$
$$\Leftrightarrow 20 - 10^{10^{-2}} < 10^{-3}n \vert \cdot 10^3$$
$$\Leftrightarrow 10^3(20-10^{-2}) < n$$
$$\Leftrightarrow 20\cdot 10^3 - 10 < n$$
$$\Leftrightarrow 20000 - 10 < n$$
$$\Leftrightarrow 19990 < n$$


b) i) Der Grenzwert der gegeben Folge ist zu bestimmen:

$$\frac{2+4n-5n^2}{10n^2+3}$$
$$\lim_{n \rightarrow \infty} \frac{2+4n-5n^2}{10n^2+3}$$
$$=\lim_{n \rightarrow \infty} \frac{-5n^2+4n+2}{10n^2+3}$$
$$=\lim_{n \rightarrow \infty} \frac{n^2(-5+\frac 4 n + \frac 2 {n^2})}{n^2(10+\frac 3 {n^2})}$$
$$=\lim_{n \rightarrow \infty} \frac{-5+\frac 4 n+\frac 2 {n^2}}{(10+\frac 3 {n^2})}$$
$$=\frac {-5} {10} = -\frac 1 2$$

ii) Bestimmen wir den Grenzwert der Folge:

$$\frac{5n^2}{10n+11} \cdot \frac{6n^2+1}{n^3+n}$$
$$\lim_{n \rightarrow \infty} \frac{5n^2}{10n+11} \cdot \frac{6n^2+1}{n^3+n}$$
$$=\lim_{n \rightarrow \infty} \frac {5n^2(6n^2+1)}{(10n+11)(n^3+n)}$$
$$=\lim_{n \rightarrow \infty} \frac{30n^4+5n^2}{10n^4+10n^2+11n^3+11n}$$
$$=\lim_{n \rightarrow \infty} \frac{30n^4+5n^2}{10n^4+11n^3+10n^2+11n}$$
$$=\lim_{n \rightarrow \infty} \frac{n^4(30+\frac 5 {n^2})}{n^4(10+\frac {11}n+\frac{10}{n^2}+\frac{11}{n^3})}$$
$$=\lim_{n \rightarrow \infty} \frac{30 + \frac 5 {n^2}}{10 + \frac{11}n+  \frac{10}{n^2} + \frac{11}{n^3}}$$
$$=\frac{30}{10} = 3$$

c) i) Berechnen wir den Grenzwert der Funktion:

$$\frac{x^2+3}{2x^3+x^2-1}$$
$$\lim_{x \rightarrow 2} \frac{x^2+3}{2x^3+x^2-1}$$
$$=\frac{2^2+3}{2(2)^3 + 2^2-1}$$
$$=\frac{4+3}{16+4-1}$$
$$= \frac 7 {19}$$

ii) Berechnen wir den Grenzwert der Funktion:

$$\frac{e^{3x}-e^{-2x}}{x}$$
$$\lim_{x \rightarrow 0} \frac{e^{3x}-e^{-2x}}{x}$$
Verwenden wir L'Hôpital zur Bestimmung des Grenzwertes:

$$=\lim_{x \rightarrow 0} \frac{3e^{3x}-(-2)e^{-2x}}{1}$$
$$=\lim_{x \rightarrow 0} 3e^{3x}+2e^{-2x}$$
$$=\lim_{x \rightarrow 0} 3e^{3x} + 2\cdot \frac 1 {e^{2x}}$$
$$=3e^0 + 2 \cdot \frac 1 {e^0}$$
$$=3 + 2 = 5$$

iii) Berechnen den Grenzwert der Funktion:

$$\frac {2-2\cos(x)}{x^2}$$

$$\lim_{x \rightarrow 0} \frac {2-2\cos(x)}{x^2}$$

Bestimmen wir den Grenzwert anhand von L'Hôpital:

$$= \lim_{x \rightarrow 0} \frac{0-(-2\sin(x))}{2x}$$
$$=\lim_{x \rightarrow 0} \frac{2\sin(x)}{2x}$$

Wenden wir L'Hôpital nun noch einmal an:

$$=\lim_{x \rightarrow 0} \frac{2\cos(x)} 2$$
$$=\lim_{x \rightarrow 0} \cos(x)$$
$$=\cos(0) = 1$$


## Aufgabe 2

a) Untersuchen wir die folgende Reihe auf Konvergenz:

$$\sum_{k=0}^{\infty} \frac{2^k}{2^k+3}$$

Versuchen wir das Quotientenkriterium zunächst:

Sei $a_n =\frac{2^n}{2^n+3}$ und

$$q = \lim_{n \rightarrow \infty} \lvert \frac{a_{n+1}}{a_n}\rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{\frac{2^{n+1}}{2^{n+1}+3}}{\frac{2^n}{2^n+3}} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{2^{n+1}}{2^{n+1}+3} \cdot \frac{2^n+3}{2^n}\rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac{2^n \cdot 2}{2^{n+1}+3} \cdot \frac{2^n+3}{2^n} \rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac 2 {2^{n+1}+3} \cdot 2^n+3 \rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac{2(2^n+3)}{2^{n+1}+3}\rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{2^{n+1}+6}{2^{n+1}+3} \rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac{2^{n+1}(1+\frac{6}{2^{n+1}})}{2^{n+1}(1+\frac{3}{2^{n+1}})} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{1+(\frac{6}{2^{n+1}})}{1+(\frac{3}{2^{n+1}})} \rvert$$
$$=\frac{1+0}{1+0} = \frac 1 1 = 1$$

Da das Verhältnis $q$ 1 entspricht, können wir durch das Quotientenkriterium keine Aussage bezüglich der Konvergenz der Folge treffen.

Versuchen wir es mal mit der monotonen Konvergenz

Betrachten wir dafür folgendes:

$$\lim_{n \rightarrow \infty} \sum_{k=0}^n \frac{2^k}{2^k+3}$$
$$=\lim_{n \rightarrow \infty} \sum_{k=0}^n \frac{2^k}{2^k(1+\frac{3}{2^k})}$$
$$=\lim_{n \rightarrow \infty} \sum_{k=0}^n \frac1{1+\frac{3}{2^k}}$$

Man sieht, dass der Summand sich bei jeder Iteration, Richtung 1 bewegt, was bedeutet, dass wir $n$ mal 1 addieren, wodurch wir also keine Beschränkung bei dieser Reihe haben und diese somit divergiert.

b) Folgende Reihe soll auf Konvergenz überprüft werden:

$$\sum_{k=0}^{\infty} ((\frac e {\pi})^k)
$$

Hierbei handelt es sich um eine geometrische Reihe, da $\frac e {\pi}$ kleiner als 1 ist und somit konvergiert diese Reihe.

c) Folgende Reihe soll auf Konvergenz überprüft werden:

$$\sum_{k=0}^{\infty} \frac{k!}{(2k)!}$$

Überprüfen wir die Konvergenz dieser Reihe anhand des Quotientenkriteriums:

Sei $a_n = \frac{n!}{(2n)!}$:

$$q = \lim_{n \rightarrow \infty} \lvert \frac{a_{n+1}}{a_n} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac {\frac{(n+1)!}{(2(n+1))!}} {\frac{n!}{(2n)!}} \rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)!}{(2(n+1))!} \cdot \frac{(2n)!}{n!} \rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac{n! \cdot (n+1)}{(2n+2)!} \cdot \frac{(2n)!}{n!} \rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac{n! \cdot (n+1)}{(2n)!(2n+1)(2n+2)} \cdot \frac{(2n)!}{n!} \rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)}{(2n+1)(2n+2)} \rvert$$

$$=\lim_{n \rightarrow \infty} \lvert \frac{n+1}{4n^2+4n+2n+2}\rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{n+1}{4n^2+6n+2} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{n^2(\frac 1 n + \frac 1 {n^2})}{n^2(4+\frac 6 n + \frac 2 {n^2})} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{\frac 1 n + \frac 1 {n^2}}{4+\frac 6 n + \frac 2 {n^2}} \rvert$$
$$=\frac 0 4 = 0$$
Hier liefert uns das Verhältnis $q = 0$, was kleiner 1 ist und somit konvergiert die Reihe.

## Aufgabe 3

a) Sei $a \in \mathbb{R}$

i) $$f(x) = e^{4x} \cdot \cos(\ln(x))$$
$$f'(x)=4e^{4x}\cdot\cos(\ln(x)) + e^{4x}\cdot\sin(\ln(x))\cdot\frac 1 x$$

ii) $$g(x)=\frac{4x^3+ax^2}{x^2+a^2}$$
$$g'(x)=\frac{(12x^2+2ax)(x^2+a^2)-2x(4x^3+ax^2)}{(x^2+a^2)^2}$$

iii) $$h(x)= \sqrt{(x+1)(x+2)} = ((x+1)(x+2))^{\frac 1 2}$$
$$h'(x)=\frac 1 2((x+1)(x+2))^{-\frac 1 2} ((x+2)(x+1))$$

b) Gegeben sei $f: \mathbb{R} \rightarrow \mathbb{R}, f(x)=\ln(4x^2+3)$

i) Wir sollen die Stelle bestimmen, an welcher der Funktionswert 2 beträgt. Dafür lösen wir folgende Gleichung: 

$$f(x)=2$$
$$\Leftrightarrow \ln(4x^2+3) = 2 \vert e^x$$
$$\Leftrightarrow 4x^2+3 = e^2 \vert -3$$
$$\Leftrightarrow 4x^2 = e^2-3 \vert \div 4$$
$$\Leftrightarrow x^2 = \frac {e^2-3}4 \vert \sqrt{}$$
$$\Leftrightarrow x = \sqrt{\frac{e^2-3}{4}} \lor x = -\sqrt{\frac{e^2-3}{4}}$$

ii) Es soll die Stelle ermittelt werden, an welcher die Steigung 1 beträgt für $f$. Dafür losen wir folgende Gleichung:

$$f'(x)=1$$

Bestimmen wir dafür zunächst $f'(x)$:
$$f'(x)=\frac 1 {4x^2+3} \cdot 8x = \frac{8x}{4x^2+3}
$$

Setzen wir das nun mit dem Wert 1 gleich:

$$f'(x)=1$$
$$\Leftrightarrow \frac{8x}{4x^2+3} = 1 \vert -1$$
$$\Leftrightarrow \frac{8x}{4x^2+3} -1 = 0$$
$$\Leftrightarrow \frac{8x}{4x^2+3} \frac{4x^2+3}{4x^2+3} = 0$$
$$\Leftrightarrow \frac{8x-(4x^2+3)}{4x^2+3} = 0$$
$$\Leftrightarrow \frac{8x-4x^2-3}{4x^2+3} = 0 \vert \cdot (4x^2+3)$$
$$\Leftrightarrow 8x-4x^2-3 = 0$$
$$\Leftrightarrow -4x^2+8x-3 = 0$$

Diese quadratische Gleichung können wir anhand der Mitternachtsformel lösen mit $a=-4, b=8, c=-3$:

$$x_1 = \frac{-8+\sqrt{8^2-(4\cdot(-4)\cdot(-3))}}{2\cdot(-4)}$$
$$=\frac{-8+\sqrt{64-(4\cdot12)}}{2\cdot(-4)}$$
$$=\frac{-8+\sqrt{64-48}}{2\cdot(-4)}$$
$$=\frac{-8+\sqrt{16}}{2\cdot(-4)}$$
$$=\frac{-8+\sqrt{16}}{-8}$$
$$=\frac{-8+4}{-8} = \frac{-4}{-8} = \frac{-1}{-2} = \frac 1 2$$



$$x_2 = \frac{-8-\sqrt{8^2-(4\cdot(-4)\cdot(-3))}}{2\cdot(-4)}$$$$=\frac{-8-\sqrt{64-(4\cdot12)}}{2\cdot(-4)}$$$$=\frac{-8-\sqrt{64-48}}{2\cdot(-4)}$$
$$=\frac{-8-\sqrt{16}}{-8}$$
$$=\frac{-8-4}{-8} = \frac{-12}{-8} = \frac {-3}{-2} = \frac 3 2$$

## Aufgabe 4

a) Gegeben ist die Funktion $f(x)=\ln(1+x)$. Bestimmen wir dessen Taylorpolynom $T_3$ mit Entwicklungspunkt $x_0=0$ anhand der Ableitungen von $f$. Bestimmen wir dafür zunächst die ersten 3 Ableitungen:

$$f(x) = \ln(1+x)$$
$$f'(x)=\frac 1 {x+1} = (x+1)^{-1}$$
$$f''(x)=-1(1+x)^{-2} = -(1+x)^{-2} = - \frac 1 {(1+x)²}$$
$$f'''(x) = -1\cdot(-2)(1+x)^{-3} = 2(1+x)^{-3} = \frac 2 {(1+x)^3}$$

Verwenden wir diese Ableitungen nun, um das Taylorpolynom aufzustellen:

$$T_3(x)=\sum_{k=0}^3\ \frac {f^{(k)}(x_0)}{k!} (x-x_0)^k$$
$$=\sum_{k=0}^3\ \frac {f^{(k)}(0)}{k!} x^k$$
$$=\frac{f(0)}{0!}x^0 + \frac{f'(0)}{1!}x+\frac{f''(0)}{2!}x^2+\frac{f'''(0)}{3!}x^3$$
$$=\frac{\ln(1+0)}{1} + \frac{(1+0)^{-1}}{1} x+ \frac{-(1+0)^2}{2}x^2+\frac{2(1+0)^3}{6}$$
$$=\frac{\ln(1)}{1} + \frac 1 1 x+ \frac{1}{2} x^2+ \frac{2}{6}x^3$$
$$=0 + x - \frac 1 2 x^2 + \frac 2 6 x^3$$
$$=0 + x - \frac 1 2 x^2 + \frac 1 3 x^3$$
$$T_3(x)= x - \frac 1 2 x^2 + \frac 1 3 x^3$$

b) Wir sollen anhand unseres Taylorpolynoms den Wert $\ln(0.5)$ annähern, jedoch müssen wir beachten, dass unser Taylorpolynom $\ln(1+x)$ annähert. Schauen wir also, was genau wir in unser Taylorpolynom einsetzen müssen anhand von folgenden:

Wir wissen, dass unser Taylorpolynom $\ln(1+x)$ annähert. Um nun von $\ln(1+x)$ auf $\ln(0.5)$ zu kommen müssen wir -0.5 einsetzen. Dies kann anhand folgender Umformung begrüundet werden:

$$\ln(0.5) = \ln(1+(-\frac 1 2)) = \ln(1 - \frac 1 2)$$
Wir müssen also in unser Taylorpolynom $-\frac 1 2$ einsetzen und das tun wir auch:

$$T_3(-\frac 1 2)=(-\frac 1 2)-\frac 1 2(-\frac 1 2)^2+\frac 1 3(-\frac 1 2)^3$$
$$=-\frac 1 2 -\frac 1 2 \cdot \frac 1 4 + \frac 1 3 \cdot (-\frac 1 8)$$
$$=-\frac 1 2 - \frac 1 8 - \frac 1 {24}$$
$$=-\frac {12}{24} - \frac 3 {24}- \frac 1 {24}$$
$$=-\frac{15}{24} - \frac 1 {24}$$
$$=-\frac {16}{24} = -\frac 2 3$$

Wir erhalten als Annhäherung also $-\frac 2 3$.

## Aufgabe 5
a) Gegeben ist die Funktion $f(x)=5x^4 - 2x^2- \frac 3{x²}$. Und wir sollen dafür eine Stammfunktion bilden, welche an der Stelle 1 den Wert 5 hat.

Zu lösen ist also:

$$\int 5x^4-2x^2-3x^{-2} dx$$

$$=x^5 - \frac 2 3 x^3+3x^{-1} + c$$

Setzen wir nun 1 in diese Stammfunktion ein, so erhalten wir $\frac {10} 3$. Jedoch soll der Wert 5 sein, was in diesem Falle $\frac {15} 3$ entspricht. Dies können wir leicht beheben, indem wir $c=\frac 5 3$ setzen, da das c beim Integrieren keine große Rolle spielt.

b)i) Folgendes Integral soll berechnet werden:

$$\int_0^{\sqrt{\pi}} 3x\sin(x^2) dx$$
Formen wir es ein bisschen um, um die Substitutionsregel anwenden zu können:

$$\frac 3 2 \int_0^{\sqrt{pi}} 2x \cdot \sin(x^2) dx$$

Wenden wir nun die vorher erwähnte Substitutionsregel an:
Sei $u = x^2$:

$$\frac 3 2 \int_{0^2}^{(\sqrt{\pi})²} \sin(u) du$$

$$=\frac 3 2 \int_0^{\pi} \sin(u) du$$
$$=\frac 3 2 [-\cos(u)]_{0}^{\pi}$$

$$=\frac 3 2 (-\cos(\pi) + \cos(0))$$
$$=\frac 3 2 (-(-1)+1) = \frac 3 2 (1+1) = \frac 3 2 \cdot 2$$
$$=3$$

c) Gegeben sind $f(x)=x^3$ und $y=8$. Der Flächeninhalt der Fläche, welche von beiden eingeschlossen wird, soll berechnet wird.

Hier können wir wie folgt vorgehen:

$$\lvert \int_0^{2} x^3 dx-\int_0^{2} 8 dx \rvert $$

Erklärung: 
	Die Intervallgrenze geht bis 2, da die eingeschlossene Fläche der beiden Funktionen bis dahin geht (versuchts mal beide Funktionen zu zeichnen und dann sieht mans eigentlich schon). Und hier tun wir die Integrale subtrahieren, da die Fläche von $y=8$ die Gesamtfläche von der Parallelen bis zur Koordinatenachse beschreibt und durch die Subtraktion mit dem $x^3$ Integral, kriegen wir genau die Fläche, die von beiden eingeschlossen wird.



$$\lvert \int_0^{2} x^3 dx-\int_0^{2} 8 dx \rvert$$
$$= \lvert [\frac 1 4 x^4]_0^2 - [8x]_0^2 \rvert$$
$$=\lvert (\frac 1 4 \cdot 16) - 16\rvert$$
$$=\lvert 4 - 16 \rvert$$
$$=\lvert -12 \rvert = 12$$

Somit beträgt der Flächeninhalt der eingeschlossenen Fläche 12 Flächeneinheiten.












