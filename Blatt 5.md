## Aufgabe 1
Sei $v \in \mathbb{Q}$ und der Wert x dB entspricht $10(\log(v))$.

a) $$v=1 = \frac 1 1 \Rightarrow 10(\log_{10} 1) = 10 \cdot 0 = 0\ dB$$
$$v = 100 = \frac {100} 1 \Rightarrow 10(\log_{10} 100) = 10 \cdot 2 = 20\ db$$

$$v = \frac 1 {1000} = 10^{-3} \Rightarrow 10(\log 10^{-3}) = 10 \cdot (-3) = -30\ db$$
$$v = \sqrt{10} = 10^{\frac 1 2} \Rightarrow 10(\log 10^{\frac 1 2}) = 10 \cdot \frac 1 2 = 5\ dB$$
$$v = 50 = 5 \cdot 10 \Rightarrow 10(\log(5 \cdot 10)) = 10(\log(5) + \log(10)) = 10(0.7+1) = 10 \cdot 1.7 = 17\ dB$$
$$v= 250 = 2 \cdot 5 \cdot 10 \Rightarrow 10(\log(5 \cdot 5 \cdot 10))$$ $$= 10(2\log(5) + \log(10)) = 10(2\cdot0.7 + 1) = 10(1.4+1) = 10 \cdot 2.4 = 24\ dB$$

b) $$40dB = 10 \cdot 4 = 10\cdot\log(10⁴) \Rightarrow v = 10⁴ = 10,000$$
$$-70dB = 10 \cdot (-7) = 10\cdot\log(10^{-7}) \Rightarrow v = 10^{-7} = \frac 1 {10,000,000}$$

## Aufgabe 2
Sei in dieser Aufgabe $a \in \mathbb{R}$.

a) $$f(x) = 4x⁴-3ax²+7x-a²$$
$$\Rightarrow f'(x) = 16x³-6ax+7$$

b) $$f(x)=x³\cdot\sin(x)$$
$$\Rightarrow f'(x)= 3x²\cdot\sin(x) + x³\cdot\cos(x)$$
c)
$$f(x)=x\sqrt x = x\cdot x^{\frac 1 2}$$
$$f'(x)=1x^{\frac 1 2} + x\cdot \frac 1 2 x^{-\frac 1 2} = \sqrt x + \frac x {2\sqrt x}$$
d)
$$f(x)=(x²-2x+2)\cdot e^x$$
$$\Rightarrow f'(x)=(2x-2)e^x + (x²-2x+2)e^x = e^x((2x-2)+(x²-2x+2))$$
$$=e^x(2x-2+x²-2x+2) = e^xx²$$
e)
$$f(x) = \frac{\ln(x)}{\sin(x)}$$
$$\Rightarrow f'(x)=\frac{\frac 1 x\cdot\sin(x) - \ln(x)\cdot\cos(x)}{\sin²(x)}$$
f)
$$f(x)=x³\cdot\sin(x)\cdot\cos(x)$$
$$f'(x)=3x²\sin(x)\cos(x)+x³\cos(x)\cos(x)+x³\sin(x)(-\sin(x))$$
$$=3x²\sin(x)\cos(x)+x³\cos²(x)-x³\sin²(x)$$
g) $$f(x)=\frac {x\ln(x)-x}{2x+1}$$
$$f'(x)=\frac{((\ln(x) + x\frac1 x)-1)(2x+1)-2(x\ln(x)-x)}{(2x+1)²}$$
$$=\frac{((\ln(x)+1-1)(2x+1)-2(x\ln(x)-x)}{(2x+1)²}$$
$$=\frac{ln(x)(2x+1)-2(x\ln(x)-x)}{(2x+1)²}$$
$$=\frac{2x\ln(x)+\ln(x)-2x\ln(x)+2x}{(2x+1)²}$$
$$=\frac{\ln(x)+2x}{(2x+1)²}$$

## Aufgabe 3

Leiten wir nun die gegebenen Funktionen ab:

a) $$f(x)=e^{4x}+\sin(3x)$$
$$\Rightarrow f'(x)=4e^{4x}+3\cos(3x)$$

b) $$f(x)=\ln(\frac {x²} 2 +1) = \ln(\frac 1 2x² + 1)$$
$$\Rightarrow f'(x)=\frac 1 {\frac 1 2 x²+1} \cdot 2x$$

c) $$f(x)=\sin(x)\cos²(x)$$$$\Rightarrow f'(x)=\cos(x)cos²(x)+\sin(x)\cdot(-2\sin(x))$$
$$=\cos³(x)-2\sin²(x)$$

d)
$$f(x)=(2x³+5x)⁴\ln(x)$$
$$\Rightarrow f'(x)=(4(2x³+5x)³(6x+5))\ln(x)+(2x³+5x)⁴\cdot\frac 1 x$$
e)
$$f(x)=\frac{e^{2x}+1}{e^{2x}-1}$$
$$\Rightarrow f'(x)=\frac{(2e^{2x})(e^{2x}-1)-(e^{2x}+1)(2e^{2x})}{(e^{2x}-1)²}$$
$$=\frac{(2e^{2x})(e^{2x}-1 - e^{2x}-1)}{(e^{2x}-1)²}$$
$$=\frac{(2e^{2x})(-2)}{(e^{2x}-1)²} = \frac{-4e^{2x}}{(e^{2x}-1)²}$$

f)
$$f(x)= x² \frac{e^{4x}}{(\ln(x))²}$$
$$\Rightarrow f'(x)=2x\frac{e^{4x}}{(\ln(x))²} + x² \frac{4e^{4x}(\ln(x))² - e^{4x}2\ln(x)\cdot \frac 1 x}{(\ln(x))⁴}$$

g) 
$$f(x)=\cos²(3e^{4x})$$
$$\Rightarrow f'(x)=2\cos(3e^{4x})\cdot12e^{4x}$$

## Aufgabe 4

Gegeben ist die Funktion:

$$f: \mathbb{R} \rightarrow \mathbb{R}, f(x)=\ln(x²+4)$$

a) Bestimmen wir die Wertemenge $W_f$ von $f$ anhand der Gleichung:

$$f(x)=a$$
Dabei ist $a \in \mathbb{R}$.

$$f(x)=a$$
$$\Leftrightarrow \ln(x²+4) = a\vert e^x$$
$$\Leftrightarrow x²+4 = e^a\vert-4$$
$$\Leftrightarrow x² = e^a-4\vert\sqrt{}$$
$$\Leftrightarrow x = \sqrt{e^a-4} \ \lor \ x = -\sqrt{e^a-4}$$

Die Bedingung für $a \in W_f$ ist:

$$e^a - 4 < 0 \vert+4$$
$$\Leftrightarrow e^a < 4 \vert \ln$$
$$\Leftrightarrow a < \ln(4)$$

Somit gilt $W_f = \{a\ \vert\ a \in \mathbb{R}: a < \ln(4)\}$


b) Um die Tangente für $f$ an der Stelle $x_0=1$ zu bestimmen, benötigen wir die Tangentengleichung:

$$y(x)=f(x_0)+f'(x_0)\cdot(x-x_0)$$

Bestimmen wir also noch $f'(x)$:
$$f'(x)=\frac 1 {x²+4} \cdot 2x = \frac {2x}{x²+4}$$

Somit ist unsere Tangente:

$$y(x)=f(1)+f'(1)\cdot(x-1)$$
$$=\ln(1²+4) + \frac{2\cdot1}{1²+4}\cdot(x-1)$$
$$y(x)=\ln(5)+\frac 2 5\cdot(x-1)$$

c) Bei einer Tangente, welche parallel zur x-Achse ist, gilt bei der Tangentengleichung:
$$y(x)=f(x_0)+f'(x_0)\cdot(x-x_0) \Rightarrow f'(x_0) = 0$$
Bestimmen wir also ein $x_0$ mit $f'(x_0)=0$:

$$f'(x_0) = 0$$
$$\Leftrightarrow \frac {2x}{x²+4} = 0\vert \cdot x²+4$$
$$\Leftrightarrow 2x = 0\vert \div 2$$
$$\Leftrightarrow x = 0$$

Somit besitzt die Funktion eine Tangente parallel zur x-Achse bei $x = 0$.

d) Um zu schauen, an welcher Stelle $f$ die Steigung $\frac 1 2$ hat, muss folgende Gleichung gelöst werden:

$$f'(x)=\frac 1 2$$
$$\Leftrightarrow \frac {2x}{x²+4} = \frac 1 2 \vert - \frac 1 2$$
$$\Leftrightarrow \frac {2x}{x²+4} - \frac 1 2 = 0$$
$$\Leftrightarrow = \frac {4x}{2(x²+4)} - \frac{x²+4}{2(x²+4)} = 0$$
$$\Leftrightarrow \frac {4x-(x²+4)}{2(x²+4)} = 0\vert \cdot 2(x²+4)$$
$$\Leftrightarrow 4x-(x²+4) = 0$$
$$\Leftrightarrow -x²+4x-4 = 0 \vert \cdot (-1)$$
$$\Leftrightarrow x²-4x+4 = 0$$
$$\Leftrightarrow (x-2)² = 0 \vert \sqrt{}$$
$$\Leftrightarrow x-2 = 0\vert + 2$$
$$\Leftrightarrow x = 2$$









