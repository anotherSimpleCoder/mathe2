## Aufgabe 1
a) Gegeben sei $\lvert x-2 \rvert > 1$

Wir führen nun folgende Fallunterscheidung durch:

#### Fall 1
$x-2 > 0$
$$ x-2 > 1   \vert +2$$
$$\Leftrightarrow x > 3$$

#### Fall 2
$\lvert x-2 < 0\rvert$

$$-(x-2) > 1$$
$$\Leftrightarrow -x+2 > 1 \vert -2$$
$$\Leftrightarrow -x > -1 \lvert \cdot (-1)$$
$$\Leftrightarrow x < 1 $$

b) Gegeben sei $x^2 + y^2 - 2x + 4y = 0$:

Lösen wir zunächst die Gleichungen $x^2 -2x = 0$ und $y^2 +4y = 0$:

$$x^2 - 2x = 0$$
$$\Leftrightarrow x^2-2x+(\frac{1}{2})^2 = (\frac{1}{2})^2$$
$$\Leftrightarrow (x-\frac{1}{2})^2 = \frac{1}{4} \vert \sqrt{}$$
$$\Leftrightarrow x-\frac{1}{2} = \frac {1}{2} \vert +\frac{1}{2}\ \lor \ x-\frac{1}{2} = - \frac{1}{2} \vert + \frac{1}{2} $$
$$\Leftrightarrow x = \frac{1}{4}\ \lor \ x = 0$$

\
$$y^2 + 4y = 0$$
$$\Leftrightarrow y^2+4y+2^2 = 2^2$$
$$\Leftrightarrow (y+2)^2 = 4 \vert \sqrt{}$$
$$\Leftrightarrow y+2 = 2 \vert -2 \ \lor \ y+2  = -2 \vert -2$$
$$\Leftrightarrow y = 0 \ \lor \ y = -4$$


Somit erhalten wir für der Menge der Punkte der Ebene: $\{(0,0)\}$


## Aufgabe 2

a) Gefordert wird ein Polynom 2ten Grades mit den Nullstellen $2+\sqrt 2$ und $2 - \sqrt 2$. Die Bedinungen können formal wie folgt ausgedrückt werden:

Sei $f: \mathbb{R} \rightarrow \mathbb{R}, f(x)=ax^2+bx+c$ und $f$ habe die Bedingungen

$$f(2 + \sqrt 2) = 0 \ \land \ f(2 - \sqrt 2) = 0$$

Dabei gehen wir wie folgt vor, um die Koeffizienten $a, b$ und $c$ zu ermitteln:

$$x = 2 + \sqrt 2 \vert -2 \ \lor \ x = 2 - \sqrt 2 \vert -2$$

$$\Leftrightarrow x-2 = \sqrt 2 \vert ()^2 \ \lor x-2 = -\sqrt 2\vert ()^2$$

$$\Leftrightarrow (x-2)^2 = 2$$
$$\Leftrightarrow x^2 - 4x + 4 = 2 \vert -2$$
$$\Leftrightarrow x^2 - 4x + 2 = 0$$
$$\Leftrightarrow 1x^2 - 4x + 2x^0 = 0$$

Unsere Koeffizienten lauten also: $a = 1, b = -4$ und $c = 2$.

b) Wir führen einen Koeffzientenvergleich zwischen $(x^2+ax+1)(x^2+bx+1)$ und $x^4+1$ aus:

Mutliplizieren wir zunächst aus:

$$(x^2+ax+1)(x^2+bx+1)$$
$$=(x^4+bx^3+x^2)(ax^3+abx^2+ax)(x^2+bx+1)$$
$$=x^4+(a+b)x^3+(x^2+abx^2+x^2)+(a+b)x+1$$
$$=x^4+(a+b)x^3+(abx^2+2x^2)+(a+b)x+1$$
$$=x^4+(a+b)x^3+(ab+2)x^2+(a+b)x+1$$

Betrachten wir nun $x^4+1$:
	Sei $f(x)=x^4+1$:

$$f(x)=x^4+1$$
$$=x^4+0x^3+0x^2+0x+1$$

Wir müssen also $a,b$ so bestimmen, sodass für diese folgendes gilt:
$$a+b = 0\ \land ab+2=0$$
Durch $a+b=0$ wissen wir: $a = -b$:
Setzen wir dies in die zweite Bedingung ein:

$$ab+2=0$$
$$\Leftrightarrow (-b)*b+2=0$$
$$\Leftrightarrow (-b)^2+2=0\ \vert -2$$
$$\Leftrightarrow (-b)^2=-2\ \vert \cdot (-1)$$
$$\Leftrightarrow b^2 = 2\ \vert \sqrt{}$$
$$\Leftrightarrow b = \sqrt 2 \ \lor b = - \sqrt 2$$
Dadurch, dass $a=-b$ gilt, können wir nun $a$ bestimmen:
$$a = -b$$
$$\Leftrightarrow a = -\sqrt 2$$
Somit erhalten wir:
$$a = -\sqrt 2 \ \land b = \sqrt 2$$
$$\lor$$
$$a = \sqrt 2 \ \land b = - \sqrt 2$$

Setzen wir a und b in den ausmulitplizierten ein:
$$x^4+(\sqrt{2}+(-\sqrt{2}))x^3+(\sqrt{2}*(-\sqrt{2}) -2)x^2+(\sqrt{2}+(-\sqrt{2}))x+1$$
Dies entspricht: $x^4 +1$.

c) Zu lösen ist: $x^3-2x+1=0$

Raten wir zunächst 1 als Nullstelle und führen Polynomdivision aus:

$$(x^3-2x+1) \div (x-1) = x^2+x+1$$

Bestimmen wir die Nullstellen von $x^2+x+1$:
$$x^2+x-1=0 \vert +1$$

$$\Leftrightarrow x^2+x = 1$$
$$\Leftrightarrow x^2+x+(\frac 1 2)^2 = 1+(\frac 1 2)^2$$
$$\Leftrightarrow (x+\frac 1 2)^2 = 1 + \frac 1 4$$
$$\Leftrightarrow (x+\frac 1 2)^2 = \frac 4 4 + \frac 1 4$$
$$\Leftrightarrow (x+\frac 1 2)^2 = \frac 5 4 \vert \sqrt{}$$
$$\Leftrightarrow x+\frac 1 2 = \frac {\sqrt{5}} {2} \vert - \frac 1 2 \ \lor x+\frac 1 2 = - \frac {\sqrt{5}} {2}\vert - \frac 1 2$$
$$\Leftrightarrow x = \frac{\sqrt{5}-1}{2} \ \lor x = \frac{-\sqrt{5}-1}{2}$$
$$\Leftrightarrow x = \frac{\sqrt{5}-1}{2} \ \lor x = \frac{-(\sqrt{5}+1)}{2}$$


## Aufgabe 3

| Term                                                         | enthält 2 | offene Umgebung | $\epsilon$ Umgebung   |
| ------------------------------------------------------------ | --------- | --------------- | --------------------- |
| $\{1,2,3\}$                                                  | ja        | nein            | nein                  |
| $\{x \vert x \in \mathbb{Q}: 0 < x < 4\}$                    | ja        | nein            | nein                  |
| $\{x \vert x \in \mathbb{R}: 0 < x \leq 4\}$                 | ja        | nein            | nein                  |
| $\{x\vert x \in \mathbb{R}: 0<x<4\} = (0;4)$                 | ja        | ja              | ja mit $\epsilon$=2   |
| $(0,4) \cap \mathbb{Q}$                                      | ja        | nein            | nein                  |
| $[0,4]\cap(1,5]\cap[2,3)$                                    | ja        | ja              | ja mit $\epsilon=1$   |
| $\{x \vert x \in \mathbb{R}: \lvert x \rvert < 3\} = (-3,3)$ | ja        | ja              | nein                  |
| $\{x \vert x \in \mathbb{R}: \vert x -2  \rvert < 0.1\}$     | ja        | ja              | ja mit $\epsilon=0.1$ |
|                                                              |           |                 |                       |

## Aufgabe 4

| Term                                                              | Infimum     | Minimum | Supremum | Maximum |
| ----------------------------------------------------------------- | ----------- | ------- | -------- | ------- |
| $\{4,7,11\}$                                                      | 4           | 4       | 11       | 11      |
| $\mathbb{N}$                                                      | 0           | 0       | -        | -       |
| $\{x \vert n \in \mathbb{N}: x = \frac{n-1}{n}\}$                 | 0           | 0       | 1        | -       |
| $\{x\vert n \in \mathbb{N} = \frac 3 {2n}\}$                      | 0           | -       |          |         |
| $\{x \vert m \in \mathbb{Z}: x = \frac m {1 + \lvert m \rvert}\}$ | -1          | -       | 1        | 1       |
| $[1,4)$                                                           | 1           | 1       | 4        | /       |
| $\{y \vert x \in (-1,1): y = \frac 1 {x^2+1}\}$                   | $\frac 1 2$ | -       | -        | -       |
|                                                                   |             |         |          |         |
