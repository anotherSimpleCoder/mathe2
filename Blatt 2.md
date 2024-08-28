## Aufgabe 1

Begeben ist die Folge $a_n = \frac {12n+4}{4n+7}\ ; \epsilon=0.001$, zu bestimmen ist $N_{\mathbb{\epsilon}}$ ab welchem gilt, dass n < $N_{\epsilon}: \lvert a_n - 3 \rvert < \epsilon:$


$$ \lvert a_n - 3 \rvert  < \epsilon \ \vert +3 $$

$$\Leftrightarrow \lvert \frac{12n+4}{4n+7} - 3 \rvert < \epsilon$$
$$\Leftrightarrow \lvert \frac {12n+4}{4n+4} - \frac {3(4n+7)}{4n+7} \rvert < \epsilon$$
$$\Leftrightarrow \lvert \frac{12n+4-3(4n+7)}{4n+7} \rvert < \epsilon$$
$$\Leftrightarrow \lvert \frac{12n+21-3(4n+7)-17}{4n+7} \rvert < \epsilon$$
$$\Leftrightarrow \lvert \frac{3(4n+7)-3(4n+7)-17}{4n+7} \rvert <\epsilon$$
$$\Leftrightarrow \lvert \frac{-17}{4n+7} \rvert <\epsilon $$
$$\Leftrightarrow \frac {17}{4n+7} < \epsilon \vert \cdot (4n+7) \div \epsilon$$
$$\Leftrightarrow \frac {17}{\epsilon} < 4n+7 \vert -7$$
$$\Leftrightarrow \frac{17}{\epsilon} - 7 < 4n \vert \div 4$$
$$\Leftrightarrow \frac 1 4 (\frac{17}{\epsilon} - 7) < n$$
$$\Leftrightarrow \frac {17}{4\epsilon} - \frac 7 4 < n$$
Wir setzen nun $\epsilon = 0.01$ ein:

$$\frac {17}{4\cdot0.01} - \frac 7 4 < n$$
$$\Leftrightarrow \frac {17}{4 \cdot \frac 1 {100}} - \frac 7 4 < n$$
$$\Leftrightarrow \frac {17} {\frac 4 {100}} - \frac 7 4 < n$$
$$\Leftrightarrow 17 \cdot \frac 1 {\frac 4 {100}} - \frac 7 4 < n$$
$$\Leftrightarrow 17 \cdot \frac {100} 4 - \frac 7 4 < n$$
$$\Leftrightarrow \frac {1700} 4 - \frac 7 4 < n$$
$$\Leftrightarrow \frac {1693} 4  < n$$
Nun bestimmen wir anhand dieser Bedingung $N_{\epsilon}$
$$N_{\epsilon} = \lceil \frac {1693} 4 \rceil$$
$$\Leftrightarrow N_{\epsilon} = 424$$

## Aufgabe 2

a) Seien:

$$a_n = (-1)^n \frac {2n}{n+1}+4 $$
$$b_n = (-1)^n \frac {2n}{n+1} +4$$
$$c_n = \frac {2n+3}{n+1}$$


| n     | 1   | 2   | 3    | 4   | 5    | 6    | 7     | 8    |
| ----- | --- | --- | ---- | --- | ---- | ---- | ----- | ---- |
| $a_n$ | 3   | 5.3 | 2.5  | 5.6 | 2.3  | 5.7  | 2.2   | 5.7  |
| $b_n$ | 3   | 4.6 | 3.5  | 4.4 | 3.6  | 4.28 | 3.75  | 4.22 |
| $c_n$ | 2.5 | 2.3 | 2.25 | 2.2 | 2.16 | 2.14 | 2.125 | 2.11 |
b) Damit eine Folge beschränkt ist, muss diese ein Infimum und Supremum haben:

| Sequence | Infimum | Minimum | Supremum | Maximum |
| -------- | ------- | ------- | -------- | ------- |
| $a_n$    | 3       | 3       | 6        | -       |
| $b_n$    | 3       | 3       | 4.6      | -       |

$a_n$ hat kein monotones Wachstumsverhalten, da sowohl
$a_1 \leq ... \leq a_n \leq a_{n+1}$ als auch $a_1 \geq ... \geq a_n \geq a_{n+1}$ nicht für $a_n$ gelten.

$b_n$ hat kein monotones Wachstumsverhalten, da sowohl
$b_1 \leq .. \leq b_n \leq b_{n+1}$ als auch $b_1 \geq ... \geq b_n \geq b_{n+1}$ nicht für $b_n$ gelten.

Somit sind $a_n, b_n$ zwar beschränkt, aber nicht monoton.

c) Um zu zeigen, dass $c_n$ durch 3 beschränkt ist, muss folgende Bedingung gelten:

$$c_n \leq 3$$
$$\Leftrightarrow \frac {2n+3}{n+1} \leq 3 \vert \cdot (n+1)$$
$$\Leftrightarrow 2n+3 \leq 3(n+1)$$ 
$$\Leftrightarrow 2n+3 \leq 3n+3 \vert -3$$
$$\Leftrightarrow 2n \leq 3n \vert \div n$$
$$\Leftrightarrow 2 \leq 3$$

Da die Aussage $2 \leq 3$ gilt, und wir dies aus der Aussage $c_n \leq 3$ umegeformt haben, gilt auch die Aussage $2 \leq 3$.

Um zu zeigen, dass $c_n$ streng monoton fallend ist, muss die Aussage $c_{n+1} < c_n$ gelten:

$$c_{n+1} < c_n$$
$$\Leftrightarrow \frac{2(n+1)+3}{(n+1)+1} < \frac{2n+3}{n+1}$$
$$\Leftrightarrow \frac {2n+2+3}{n+2} < \frac {2n+3}{n+1}$$
$$\Leftrightarrow \frac{2n+5}{n+2} < \frac{2n+3}{n+1} \vert \cdot (n+2)$$
$$\Leftrightarrow 2n+5 < \frac {(2n+3)(n+2)}{n+1} \vert \cdot (n+1)$$

$$\Leftrightarrow (2n+5)(n+1) < (2n+3)(n+2)$$
$$\Leftrightarrow 2n² + 2n + 5n + 5 < 2n²+4n+3n+6$$
$$\Leftrightarrow 2n² + 7n + 5 < 2n² + 7n + 6 \vert - (2n² + 7n) $$
$$\Leftrightarrow 5 < 6 $$

Da die Aussage $5<6$ eine Tautologie ist und aus der Aussage $c_{n+1} < c_n$, ist die Aussage $c_{n+1} < c_n$ korrekt.

d) Durch den Vorzeichenwechsel mit $(-1)^n$ in $a_n$ und $a_n$ kein monotones Wachstumsverhalten hat, konvergiert $a_n$ nicht (siehe monotone Konvergenz).

e) Sei $g_1 = lim_{n \rightarrow \infty}\ b_n$. Bestimmen wir also zunächst $lim_{n \rightarrow \infty}\ b_n$:

$$lim_{n \rightarrow \infty} \ b_n$$
$$= lim_{n \rightarrow \infty}\ (-1)^n \frac 2 {n+1} + 4 = 4$$
Somit ist $g_1 = 4$.

Nun muss gezeigt werden, dass folgendes gilt:
$$lim_{n \rightarrow \infty}\ (b_n - g_1) = 0$$
$$\Leftrightarrow lim_{n \rightarrow \infty}\ (b_n - 4) = 0$$
$$\Leftrightarrow lim_{n \rightarrow \infty}\ ((-1)^n \frac 2 {n+1} + 4 - 4) = 0$$
$$\Leftrightarrow lim_{n \rightarrow \infty}\ (-1)^n \frac 2 {n+1} = 0$$

Sei $g_2 = lim_{n \rightarrow \infty}\ c_n$. Bestimmen wir zunächst $lim_{n \rightarrow \infty}\ c_n$:
$$lim_{n \rightarrow \infty}\ c_n$$
$$= lim_{n \rightarrow \infty} \frac{2n+3}{n+1}$$
$$=lim_{n \rightarrow \infty} \frac {2n}{n+1} + \frac 3 {n+1}$$
$$= lim_{n \rightarrow \infty} \frac{n\cdot2}{n(1+\frac 1 n)} + \frac 3 {n+1}$$
$$=lim_{n \rightarrow \infty} \frac 2 {1+\frac 1 n} + \frac 3 {n+1}$$

$$= lim_{n \rightarrow \infty} \frac 2 {1+ \frac 1 n} + \frac {n \cdot \frac 3 n}{n(1+\frac 1 n)}$$
$$= lim_{n \rightarrow \infty} \frac 2 {1+\frac 1 n} + \frac {\frac 3 n} {1 + \frac 1 n} = 2$$
Somit ist $g_2 = 2$. Wir setzen $g_2$ nun in $(c_n - g_2) \leq 0$ ein:

$$(c_n - g_2) \leq 0$$
$$\Leftrightarrow (c_n - 2) \leq 0$$
$$\Leftrightarrow \frac {(2n+3)}{n+1} - 2 \leq 0$$
$$\Leftrightarrow \frac {(2n+3)}{n+1} - \frac {2(n+1)}{n+1} \leq 0$$
$$\Leftrightarrow \frac {(2n+3)-2(n+1)} {n+1} \leq 0$$
$$\Leftrightarrow \frac {(2n+3)-(2n+2)}{n+1} \leq 0$$
$$\Leftrightarrow \frac 1 {n+1} \leq 0$$

## Aufgabe 3

Eine Nullfolge, die wir nehmen können ist $a_n = \frac {(-1)^n} n$ und eine Folge, welche bestimmt gegen $\infty$ divergiert ist $b_n = n$. Das Produkt beider ist wie folgt:

$$c_n = a_n \cdot b_n$$
$$=\frac {(-1)^n} n \cdot n$$
$$= (-1)^n$$

Dabei ist $c_n$ zwar nicht konvergent, jedoch trotzdem beschränkt mit 1 als obere und -1 als untere Schranke.

## Aufgabe 4

a) Bestimmen wir den Grenzwert von dem folgendem Term mit Grenzwertgesetzen:
$$lim_{n \rightarrow \infty}\ \frac {103n²-53n+41}{n²+5}$$
$$= lim_{n \rightarrow \infty}\ \frac {n²(103-\frac {53} n + \frac {41} {n²})} {n²(1+\frac 5 {n²})}$$
$$= lim_{n \rightarrow \infty}\ \frac{103 - \frac {53} n + \frac {41}{n²}}{1 + {\frac 5 {n²}}}$$
$$=\frac {103} 1 = 103$$

b) Bestimmen wir den Grenzwert von dem folgenden Termin mit Grenzwertgesetzen:
$$lim_{n \rightarrow \infty}\ \frac {103n³}{n²+5}-\frac{103n²}{n+19}$$
$$=lim_{n \rightarrow \infty}\ \frac {103n³\cdot(n+19)}{(n²+5)(n+19)}-\frac {103n²(n²+5)}{(n²+5)(n+19)}$$
$$=lim_{n \rightarrow \infty} \frac{103n^4+1957n³}{(n²+5)(n+19)}-\frac{103n^4+515n²}{(n²+5)(n+19)}$$
$$=lim_{n \rightarrow \infty}\ \frac{103n^4+1957n³-103n^4-515n²}{(n²+5)(n+19)}$$
$$=lim_{n \rightarrow \infty} \frac{1957n³-515n²}{(n²+5)(n+19)}$$
$$=lim_{n \rightarrow \infty} \frac{1957n³-515n²}{n³+19n²+5n+95}$$
$$=lim_{n \rightarrow \infty}\ \frac{n³(1957-\frac{515}{n})}{n³(1+\frac {19} n + \frac 5 {n²} + \frac {95}{n³})}$$
$$=lim_{n \rightarrow \infty}\ \frac {1957-\frac{515}n} {1+\frac{10}n+\frac{5}{n²}+\frac{95}{n³}}$$
$$=\frac {1957} 1 = 1957$$
## Aufgabe 5

Gegeben ist die Folge:
$$a_1 = 1$$ $$\ a_{n+1}=\frac 1 2(a_n+\frac 3 {a_n}) für\ n\geq2$$
a) Betrachten wir zunächst die ersten fünf Folgeglieder:

$$a_1 = 1$$
$$a_2 = \frac 1 2(a_1+\frac 3 {a_1}) = \frac 1 2 (1+3) = \frac 1 2 \cdot 4 = 2$$
$$a_3 = \frac 1 2 (a_2 + \frac 3 {a_2}) = \frac 1 2(2+\frac 3 2) = \frac 1 2 \cdot \frac 7 2 = \frac 7 4 = 1.75$$
$$a_4 = \frac 1 2 (a_3 + \frac 3 {a_3}) = \frac 1 2 (\frac 7 4+\frac 3 {\frac 7 4}) = \frac 1 2 (\frac 7 4 + 3\cdot \frac 4 7) = \frac 1 2 (\frac 7 4 + \frac {12} 7) = \frac 7 8 + \frac {12}{14} = 1.7321$$
$$a_5 = \frac 1 2 (a_4 + \frac 3 {a_4}) = 1.7320$$ 
b) Sei $g$ der Grenzwert unserer Folge. Zu zeigen ist, dass $g$ der Gleichung
$$g = \frac 1 2 (g+\frac 3 g)$$ genügt. Dies tun wir durch Grenzwertsätze. Betrachten wir zunächst den Grenzwert von $a_n$:

$$lim_{n \rightarrow \infty}\ a_n$$
$$=lim_{n \rightarrow \infty}\ \frac 1 2 (a_n + \frac 3 {a_n})$$
$$=lim_{n \rightarrow \infty}\ (\frac 1 2 \cdot a_n) + \frac 1 2 \cdot \frac 3 {a_n}$$
$$=lim_{n \rightarrow \infty}\ (\frac 1 2 \cdot a_n) + \frac 3 2 \cdot \frac 1 {a_n}$$

Sei $b_n = \frac 1 {a_n}$ :
$$\Rightarrow lim_{n \rightarrow \infty}\ (\frac 1 2 \cdot a_n) + \frac 3 2 \cdot b_n$$
$$=lim_{n \rightarrow \infty}\ \frac 1 2 \cdot a_n + \frac 3 2 \cdot b_n$$
Wir tun nun $b_n$ rücksubstituieren:
$$=lim_{n \rightarrow \infty}\ \frac 1 2 \cdot a_n + \frac 3 2 \cdot \frac 1 {a_n}$$

Wir wissen, dass $g$ unser Grenzwert für $a_n$ ist. Nutzen wir dies in Kombination mit dem ersten und dritten Grenzwertsatz, so erhalten wir folgenden Grenzwert:

$$\frac 1 2 \cdot g + \frac 3 2 \cdot \frac 1 g$$
$$= \frac 1 2 (g+\frac 3 g)$$
Dies entspricht unserer Gleichung $g = \frac 1 2 (g + \frac 3 g)$ und somit genügt g dieser.

c) Bestimmen wir nun anhand der Gleichung den Grenzwert $g$:

$$g = \frac 1 2 (g+\frac 3 g)$$
$$\Leftrightarrow g = \frac 1 2 g + \frac 3 2 \cdot \frac 1 g \vert - \frac 1 2g$$
$$\Leftrightarrow \frac 1 2 g = \frac 3 2 \cdot \frac 1 g \vert \cdot g$$
$$\Leftrightarrow \frac 1 2 g² = \frac 3 2 \vert \cdot 2$$
$$\Leftrightarrow g² = 3 \vert \sqrt{}$$
$$\Leftrightarrow g = \sqrt 3 \ \lor g = - \sqrt 3$$



