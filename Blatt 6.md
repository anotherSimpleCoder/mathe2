
## Aufgabe 1
a) Es soll der Grenzwert des folgenden Terms bestimmt werden:

$$\frac{x⁴-2x²+1}{x²-2x+1}$$
Würden von diesem Term so den Grenzwert nehmen, bekämen wir $\frac 0 0$. Dementsprechend nutzen wir das Gesetz von L'Hôpital:

$$\lim_{x\rightarrow1}\ \frac{x⁴-2x²+1}{x²-2x+1}$$
$$=\lim_{x\rightarrow 1}\ \frac{4x³-4x}{2x-2}$$
Auch hier bekämen wir wieder als Grenzwert $\frac 0 0$. Dementsprechend wenden wir L'Hôpital nochmal an:

$$\lim_{x\rightarrow 1} \frac{12x²-4}{2} = \frac {12-4} 2 = \frac 8 2 = 4$$

b) Gegeben ist der Term:

$$\frac x {e^x}$$
Würden wir den Grenzwert dieses Terms wie üblich betrachten bekämen wir den Grenzwert $\frac {\infty}{\infty}$. Dementsprechend verwenden wir den Satz von L'Hôpital:

$$\lim_{x\rightarrow \infty} \frac x {e^x}$$
$$=\lim_{x \rightarrow \infty} \frac 1 {e^x} = 0$$

c) Gegeben ist der Term:
$$\lim_{x \rightarrow \infty} \frac{x²}{e^x}$$

Würden wir den Grenzwert dieses Terms wie üblich betrachten bekämen wir den Grenzwert $\frac {\infty}{\infty}$. Dementsprechend verwenden wir den Satz von L'Hôpital:

$$\lim_{x \rightarrow \infty} \frac {x²}{e^x}$$
$$=\lim_{x \rightarrow \infty} \frac{2x}{e^x}$$
Für diesen Term würden wir trotzdem den Grenzwert $\frac {\infty}{\infty}$ erhalten. Dementsprechend wenden wir den Satz von L'Hôpital nochmal an:

$$=\lim_{x \rightarrow \infty} \frac 2{e^x} = 0$$

d) Gegeben ist der Term:

$$\lim_{x \rightarrow \frac{\pi}4} \frac {x - \frac {\pi}4}{\sin(x)-\cos(x)}$$
Würden wir den Grenzwert dieses Terms wie üblich betrachten bekämen wir den Grenzwert $\frac 0 0$. Dementsprechend verwenden wir den Satz von L'Hôpital:

$$\lim_{x \rightarrow \frac{\pi}4} \frac 1 {\cos(x)-(-\sin(x))}$$
$$=\lim_{x\rightarrow \frac{\pi}4} \frac 1 {\cos(x)+\sin(x)}$$
$$=\frac 1 {\cos(\frac {\pi} 4)+\sin(\frac {\pi} 4)}$$

e) Gegeben ist der Term:

$$\lim_{x \rightarrow \infty} \frac x {2x+\sin(x)}$$
Würden wir den Grenzwert wie normal berechnen, erhalten wir $\frac {\infty}{\infty}$. Dementsprechend nutzen wir den Satz von L'Hôpital:

$$\lim_{x \rightarrow \infty} \frac x {2x+\sin(x)}$$
$$=\lim_{x \rightarrow \infty} \frac 1 {2+\cos(x)}$$
Hier haben wir das Problem, dass uns L'Hôpital auch nicht weiterhelfen wird, da die Ableitungen von $\sin(x)$ und $\cos(x)$ niemals einen konvergenten Term erreichen werden, wodurch wie durch L'Hôpital den Grenzwert nicht bestimmen können.


## Aufgabe 2
Gegeben ist die folgende Funktion:

$$f: \mathbb{R} \rightarrow \mathbb{R}: f(x)=\ln(x²+4)$$
a) Die Extrema können wir bestimmen durch $f'(x)=0$:

$$f'(x)=0$$
$$\Leftrightarrow \frac 1 {x²+4} \cdot (2x) = 0$$
$$\Leftrightarrow \frac {2x}{x²+4} = 0 \vert \cdot (x²+4)$$
$$\Leftrightarrow 2x = 0\vert \div 2$$
$$\Leftrightarrow x = 0$$

Setzen wir die Extremstelle und erhalten den y-Wert:

$$f(0)=\ln(0²+4)$$
$$=\ln(4)$$

Somit ist das Extremum: $(0 \vert \ln(4))$


Die Wendepunkte können wir bestimmen durch $f''(x)=0$:
$$f''(x)=0$$
$$\Leftrightarrow \frac{2(x²+4)-2x(2x)}{(x²+4)²} = 0$$
$$\Leftrightarrow \frac{2x²+8-4x²}{(x²+4)²} =0$$
$$\Leftrightarrow \frac{-2x²+8}{(x²+4)²}=0\vert\cdot(x²+4)²$$
$$\Leftrightarrow -2x²+8 = 0\vert-8$$
$$\Leftrightarrow -2x²=-8\vert \div(-2)$$
$$\Leftrightarrow x² = 4\vert \sqrt{}$$
$$\Leftrightarrow x = 2 \ \lor x = -2$$

Setzen wir $x=2$ und $x=-2$ ein um die y-Werte der Wendepunkte zu bestimmen:

$$f(2) = \ln(2²+4) = \ln(4+4) = \ln(8)$$
$$f(-2) = \ln((-2)²+4) = \ln(4+4) = \ln(8)$$

Somit sind die Wendepunkte von $f$: $(2\vert\ln(8))\ und\ (-2\vert\ln(8))$

b)

## Aufgabe 3

Gegeben ist die Funktion:
$$f: \mathbb{R} \rightarrow \mathbb{R}, f(x)=\frac{e^x-e^{-x}}{e^x+e^{-x}}$$

a) Um zu zeigen, dass $f$ auf ganz $\mathbb{R}$ definiert ist, bestimmen wir die Nullstellen des Nennerterms.

$$e^x+e^{-x} = 0 \vert -e^{-x}$$
$$\Leftrightarrow e^x = -e^{-x}\vert\ln$$
$$\Leftrightarrow x = -(-x)$$
$$\Leftrightarrow x = x\vert - x$$
$$\Leftrightarrow 0 = 0$$

Da wir keine Nullstellen haben, ist $f$ auf ganz $\mathbb{R}$ definiert.

b) Um zu zeigen, dass $f$ streng monoton wachsend ist, müssen wir zeigen:

$$f'(x) > 0$$
Bestimmen wir zunächst $f'(x)$:

$$f'(x)=\frac{(e^x+e^{-x})(e^x+e^{-x})-(e^x-e^{-x})(e^x-e^{-x})}{(e^x+e^{-x})²}$$
$$=\frac{(e^x+e^{-x})²-(e^x-e^{-x})²}{(e^x+e^{-x})²}$$
$$=\frac{(e^x+e^{-x})}{(e^x+e^{-x})²} - \frac{(e^x-e^{-x})²}{(e^x+e^{-x})²}$$
$$=1-\frac{(e^x-e^{-x})²}{(e^x+e^{-x})²}$$

Setzen wir $f'(x)$ in die Bedingung ein:

$$1-\frac{(e^x-e^{-x})²}{(e^x+e^{-x})²} > 0 \vert + \frac{(e^x-e^{-x})²}{(e^x+e^{-x})²}$$
$$\Leftrightarrow 1 > \frac{(e^x-e^{-x})²}{(e^x+e^{-x})²}$$

## Aufgabe 4

Seien

$$e^x = \sum_{k=0}^{\infty} \frac{x^k}{k!},\ f:\mathbb{R}\rightarrow\mathbb{R}, f(x)=e^{-4x}$$
a) Bestimmen wir die Taylorannäherung von $f$ Genauigkeit von 3 Termen und dem Entwicklungspunkt $x_0=0$:

$$T_3(x)=\sum_{k=0}^{3} \frac{f^{(k)}(0)}{k!}\cdot(x-0)^k$$
$$=\frac{f(0)}{0!}x⁰ + \frac{f'(0)}{1!}x + \frac{f''(0)}{2!}x²+\frac{f'''(0)}{3!}x³$$

Bestimmen wir dafür zunächst $f'(x), f''(x)$ und $f'''(x)$:

$$f'(x)=-4e^{-4x}$$
$$f''(x)=16e^{-4x}$$
$$f'''(x)=-64e^{-4x}$$
Setzen wir die Ableitungen nun in unser Taylorpolynom ein:

$$\frac{e^{-4\cdot0}}{0!} x⁰+\frac{-4e^{-4\cdot0}}{1!}x+ \frac{16e^{-4\cdot0}}{2!}x² + \frac{-64e^{-4\cdot0}}{3!}x³$$
$$=1-4x+\frac{16}{2}x²-\frac{64}6x³$$
$$=1-4x+8x^2-\frac{64}6x³$$
b) Bilden wir nun ein abstrakteres Gesetz für unsere Taylorreihe abhänging der Ableitungsvorschriften von $f$. Bei genauerem Hinschauen, fällt uns folgendes Muster auf:

$$\sum_{k=0}^{\infty} \frac{(-4)^k}{k!} x^k$$
Und dies ist die Taylorreihe unserer Funktion $f$.

c) Bestimmen wir nun die Taylorreihe anhand der Taylorreihe von $e$, welche am Anfang gegeben war.

$$e^x = \sum_{k=0}^{\infty} \frac{x^k}{k!}$$
$$\Rightarrow e^{-4x} = \sum_{k=0}^{\infty} \frac{(-4x)^k}{k!}$$
Die Taylorreihe $T_n(x)$ lautet also:

$$T_n(x)= \sum_{k=0}^n \frac{(-4x)^k}{k!}$$
Das Taylorpolynom $T_3(x)$ würde mit dieser Taylorreihe wie folgt aussehen:

$$T_3(x) = \frac{(-4x)⁰}{0!} + \frac{(-4x)¹}{1!} + \frac{(-4x)²}{2!} + \frac{(4x)³}{3!}$$

$$=\frac{1}{1} - \frac{4x}{1} + \frac{16x²}{2} - \frac{64x³}{6}$$
$$= 1 - 4x + \frac {16}2 x² - \frac{64}{6}x³$$


$$ T_3(x) = 1-4x+8x²-\frac{64}6x³$$

d) Gegeben sei unser Taylorpolynom $T_3(x)$ für unsere Funktion $f$ und wir sollen damit nun $e$ annähern. Aktuell gilt:

$$T_3(x) \approx e^{-4x}$$
Um e also zu erhalten müssen wir wie folgt vorgehen:

$$e^{-4x} \approx T_3(x)$$$$e^{-4\cdot(-\frac 1 4)} \approx T_3(-\frac 1 4)$$
$$\Leftrightarrow e¹ \approx T_3(-\frac 1 4)$$
$$\Leftrightarrow e \approx T_3(-\frac 1 4)$$
$$\Leftrightarrow e \approx 1 - 4\cdot(-\frac 1 4) + 8\cdot((-\frac 1 4)²) - \frac {64}6(-\frac 1 4)³$$
$$\Leftrightarrow e \approx 1 - (-1) + 8(\frac 1 {16}) + \frac {64}6 \cdot \frac 1 {64}$$
$$\Leftrightarrow e \approx 1+1+\frac 1 2 + \frac 1 6$$
$$\Leftrightarrow e \approx 2 + \frac 1 2 + \frac 1 6$$
$$\Leftrightarrow e \approx \frac {12} 6 + \frac 3 6 + \frac 1 6$$
$$\Leftrightarrow e \approx \frac {16}6$$

