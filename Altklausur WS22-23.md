## Aufgabe 1

a) Es soll eine Folge angegeben werden, welche zwar beschränkt, aber nicht konvergent ist.

Eine solche Folge ist $a_n = (-1)^n$. Beschränkt ist sie, da dessen Supremum 1 und Infimum -1 ist. Jedoch ist $a_n$ nicht beschränkt, da diese bestimmt divergiert.

b) Gegeben sei die Folge:

$$a_n = \frac{n^3+n+2}{6n^7+5n^4+n^2+1}$$

Dessen Grenzwert soll bestimmt:

$$\lim_{n \rightarrow \infty} a_n$$
$$=\lim_{n \rightarrow \infty} \frac{n^3+n+2}{6n^7+5n^4+n^2+1}$$
$$=\lim_{n \rightarrow \infty} \frac{n^7(\frac 1 {n^4}+\frac 1 {n^6}+\frac 2 {n^7})}{n^7(6+\frac 5 {n^3}+\frac 1 {n^5} + \frac 1 {n^7})}$$

$$=\lim_{n \rightarrow \infty} \frac{\frac 1 {n^4}+\frac 1 {n^6}+\frac 2 {n^7}}{6+\frac 5 {n^3}+\frac 1 {n^5} + \frac 1 {n^7}}$$
$$=\lim_{n \rightarrow \infty} \frac{0+0+0}{6+0+0+0}$$
$$=\lim_{n \rightarrow \infty} \frac 0 6 = 0$$

c) Die Summe und Differenz zweier divergenter Folgen, muss nicht immer divergent sein.

**Gegenbeispiel:**
1) Summe zweier divergenter Folgen:
		Gegeben seien  $a_n=n, b_n = -n$:

$$c_n = a_n+b_n$$
$$c_n = n + (-n)$$
$$c_n = n-n$$
$$c_n = 0$$

In dem Fall konvergiert $c_n$ (die Summe von $a_n$ und $b_n$)

2) Differenz zweier divergenter Folgen:
		Gegeben seien $a_n=n$ und $b_n = n$:

$$c_n = a_n - b_n$$
$$c_n = n-n$$
$$c = 0$$

In diesem Fall konvergiert $c_n$ (die Differenz von $a_n$ und $b_n$).

Jedoch ist das Produkt zweier divergenter Folgen , immer divergent.


d) Gegeben sei die Folge

$$b_n = \frac 1 {n^2}(1+2+3+...+n)$$

Führen wir die folgende Umformung durch.
$$b_n = \frac 1 {n^2}(1+2+3+...+n)$$
$$=\frac 1 {n^2} \cdot \sum_{i=1}^n i$$
$$=\frac 1 {n^2} \cdot \frac{n(n+1)}{2}$$
$$=\frac 1 {n^2} \cdot \frac {n^2+n}2$$
$$=\frac{n^2+n}{2n^2}$$

Bestimmen wir nun dessen Grenzwert:
$$\lim_{n \rightarrow \infty} \frac{n^2+n}{2n^2}$$
$$=\lim_{n \rightarrow \infty} \frac{n^2(1+\frac 1 n)}{n^2\cdot2}$$
$$=\lim_{n \rightarrow \infty} \frac{1+\frac 1 n}{2}$$
$$=\frac {1+0}2 = \frac 1 2$$

## Aufgabe 2

a) i) Gegeben ist die folgende Reihe:

$$\sum_{n = 1}^{\infty} \frac{n^4}{5^n}$$
Prüfen wir dessen Konvergenzverhalten anhand des Quotientenkriteriums:

$$q = \lim_{n \rightarrow \infty} \lvert \frac{a_{n+1}}{a_n} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{\frac{(n+1)^4}{5^{n+1}}}{\frac{n^4}{5^n}} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)^4}{5^{n+1}} \cdot \frac{5^n}{n^4} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)^4}{5^n \cdot 5} \cdot \frac{5^n}{n^4} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)^4}{5} \cdot \frac 1{n^4} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{(n+1)^4}{5n^4} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{n^4+4n^3+6n^2+4n+64}{5n^4} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{n^4(1 + \frac 4 n + \frac 6 {n^2} + \frac 4 {n^3} + \frac{64}{n^4})}{n^4\cdot5} \rvert$$
$$=\lim_{n \rightarrow \infty} \rvert \frac{1 + \frac 4 n + \frac 6 {n^2} + \frac 4 {n^3} + \frac{64}{n^4}}{5} \rvert$$
$$=\frac {1+0+0+0+0}{5} = \frac 1 5$$

Da das Verhältnis $q = \frac 1 5$ kleiner als 1 ist, konvergiert die Reihe.

b) Gegeben ist die folgende Reihe:

$$\sum_{n=1}^{\infty} \frac 3 {2n+2}$$
Prüfen wir dessen Konvergenzverhalten anhand des Quotientenkriteriums:

$$q = \lim_{n \rightarrow \infty} \lvert \frac{a_{n+1}}{a_n} \rvert$$
$$= \lim_{n \rightarrow \infty} \lvert \frac {\frac 3 {2(n+1)+2}} {\frac 3 {2n+2}} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac 3 {2(n+1)+2} \cdot \frac {2n+2} 3 \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac 1 {2(n+1)+2} \cdot (2n+2) \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac 1 {2n+2+2} \cdot (2n+2) \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac{2n+2}{2n+4} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac {2n(1+\frac 1 n)}{2n(1 + \frac 2 n)} \rvert$$
$$=\lim_{n \rightarrow \infty} \lvert \frac {1+\frac 1 n}{1 + \frac 2 n} \rvert$$
$$=\frac {1+0}{1+0} = \frac 1 1 = 1$$
Da das Verhältnis $q=1$ ist, können wir über das Quotientenkriterium keine Aussage bezüglich der Konvergenz dieser Reihe tätigen.

b) Die Reihe:

$$\sum_{n=0}^{\infty} e^n \cdot 5^{-n}$$

Führen wir folgende Umformungen durch:

$$\sum_{n=0}^{\infty} \frac{e^n}{5^n} = \sum_{n=0}^{\infty} (\frac{e}{5})^n$$
Mit $\frac e 5 < 1$ handelt es sich bei dieser Reihe um eine geometrische Reihe, welche konvergiert.

Bestimmen wir nun dessen Grenzwert:

$$\lim_{n \rightarrow \infty} \sum_{i=0}^n (\frac{e}{5})^i$$
$$=\frac 1 {1-\frac e 5} = \frac 1 {\frac 5 5 - \frac e 5}$$
$$=\frac 1 {\frac {5-e}5} = \frac 5 {5-e}$$

## Aufgabe 3
a)

| Funktion  | n-te Ableitung    |
| --------- | ----------------- |
| $e^x$     | $e^x$             |
| $x^n$     | $n \cdot x^{n+1}$ |
| $x^{n-1}$ | $(n-1)x^{n-2}$    |
| $e^{2x}$  | $2^ne^{2x}$       |
|           |                   |

b) i) Gegeben ist die Funktion:
$$f(x)=10x^2 \cdot (4x+7)^{20}$$
$$f'(x)=20x(4x+7)^{20} + 10x^2\cdot80(4x+7)^{19}$$
$$f'(x)=20x(4x+7)^{20} + 800x^2(4x+7)^{19}$$
ii) Gegeben sei die Funktion:
$$g(x)=\sin((x+1)(x-1))$$
$$=\sin(x^2-1)$$

$$g'(x)=\cos(x^2-1)\cdot2x$$


iii) Gegeben sei die Funktion:
$$h(x)=(\frac {x+1}{x-1})^2$$

$$h'(x)= 2(\frac {x+1}{x-1})(\frac{(x+1)-(x-1)}{(x-1)^2})$$
$$= 2(\frac {x+1}{x-1})(\frac{x^2-1}{(x-1)^2})$$

## Aufgabe 4

Gegeben sei die Funktion: $f(x)=x^2+2\sin(x)$

a) Bestimmen wir dessen 4 Ableitungen:

$$f'(x)=2x+2\cos(x)$$
$$f''(x)=2+(-2\sin(x)) = 2-\sin(x)$$
$$f'''(x)=-2\cos(x)$$
$$f''''(x)=2\sin(x)$$

b) Berechnen wir das Taylor-Polynom anhand der vorigen gelbildeten Ableitungen:

$$T_4(x)= \sum_{k=0}^4 \frac{f^{(k)}(x_0)}{k!} (x-x_0)^k$$
Mit $x_0 = 0$ sieht unser Taylorpolynom wiefolgt aus:

$$T_4(x)= \sum_{k=0}^4 \frac{f^{(k)}(0)}{k!} x^k$$
$$=\frac{f(0)}{0!}x^0 + \frac{f'(0)}{1!}x + \frac{f''(0)}{2!}x^2 + \frac{f'''(0)}{3!}x^3 + \frac{f''''(0)}{4!}x^4$$
$$=\frac{f(0)}{1} + \frac{f'(0)}{1}x + \frac{f''(0)}{2}x^2 + \frac{f'''(0)}{3!}x^3 + \frac{f''''(0)}{4!}x^4$$
$$=f(0) + f'(0)x + \frac{f''(0)}{2} x^2+ \frac{f'''(0)}{6} x^3+ \frac{f''''(0)}{24}x^4$$
$$=(0^2+2\sin(0)) + (2\cdot0+2\cos(0))x + \frac{(2 - 2\sin(0))}{2}x^2+\frac{-2\cos(0)}{6}x^3 + \frac{2\sin(0)}{24}x^4$$
$$=0+2x+\frac 2 2x^2 + \frac{-2}6x^3+0x^4$$
$$=2x+x^2-\frac 2 6 x^3$$
$$=2x+x^2-\frac 1 3 x^3$$

c) Wir wissen:

$$f(\frac 1 2) = 1.208851$$

Bestimmen wir nun $T(\frac 1 2)$:

$$T(\frac 1 2) = 2(\frac 1 2) + (\frac 1 2)^2 - \frac 1 3 (\frac 12)^3$$
$$=1+\frac 1 4 - \frac 1 3 \cdot \frac 1 8$$
$$=1 + \frac 1 4 - \frac 1 {24}$$
$$=\frac{24}{24} + \frac 6 {24} - \frac 1 {24}$$
$$=\frac {30}{24} - \frac 1 {24}$$
$$=\frac {29}{24}$$

Der Bruch $\frac {29}{24}$ entspricht $1.20833$ und stimmt mit $f(\frac 1 2)$ in 3 Stellen hinter dem Komma überein.


## Aufgabe 5

a) Gegeben seien die Funktionen:

$$f(x) = x^{-\frac 3 2}; g(x)=2x\cdot e^{3x^2}$$
Bestimmen wir deren Stammfunktionen:

$$\int x^{-\frac 3 2} dx$$
$$= \frac 1 {- \frac 3 2 + 1} x^{-\frac 3 2 +1}$$
$$=\frac 1 {-\frac 3 2 + \frac 2 2} x^{-\frac 3 2 +1}$$
$$=\frac 1 {-\frac 1 2} x^{-\frac 1 2}$$
$$=2x^{-\frac 1 2}$$

$$\int 2x\cdot e^{3x^2} dx$$
$$=\frac 1 3 \int 6x \cdot e^{3x^2} dx$$
$$=\frac 1 3 (\frac 1 2(e^{3x^2})^2)$$
$$=\frac 1 6 (e^{3x^2})^2$$


b) Gegeben seien die Funktionen 

$$f(x)= x^2; g(x)=8x^2$$

Um deren eingeschlossene Fläche im Intervall $[-3;3]$ zu bestimmen muss folgende Berechnung durchgeführt werden:

$$\lvert \int_{-3}^3 f(x) dx - \int_{-3}^3 g(x) dx \rvert$$
$$=\lvert \int_{-3}^3 x^2 dx - \int_{-3}^3 8-x^2 dx \rvert$$
$$=\lvert[\frac 1 3 x^3]_{-3}^3 - [8x - \frac 1 3 x^3]_{-3}^3 \rvert$$
$$=\lvert(\frac {27}3 + \frac {27}3) - ((24-\frac {27}3) - (-24+\frac {27}3))\rvert$$
$$=\lvert(9+9) - ((24-9)-(-24+9))\rvert$$
$$=\lvert18 - (15+24-9)\rvert$$
$$=\lvert18 - (15+15) \rvert = \lvert 18 - 30 \rvert = \lvert -12 \rvert = 12$$
