#math #calculo #derivadas 

### Teorema
 São válidas as fórmulas de derivação:
$$1) f(x)=e^x \implies f'(x) = e^x$$

$$2) g(x) = \ln x \implies g'(x) = \frac{1}{x}, x >0$$

#### Demonstração
1)

$$\begin{align} 
 f'(x) = \lim_{ h \to 0}{\frac{e^{(x+h)} - e^x}{h}} \\
 \\ =\lim_{ h \to 0}{\frac{e^x(e^h - 1)}{h}} \\ 
 \\ \text{sendo } \lim_{ h \to 0}{\frac{e^h-1}{h}}=1 \\
 \\ \text{Portanto, } f'(x) = e^x 
\end{align}$$
2)
$$\begin{align}
g'(x) = \lim_{ h \to 0 }{\frac{\ln (x+h) - \ln x}{h}} \\
\\ = \lim_{ h \to 0 }{\frac{1}{h}\ln \left( 1 + \frac{h}{x} \right)},  \text{ Seja } u=\frac{h}{x} \\
=\lim_{ u \to 0 }{\ln(1+u)^{\frac{1}{xu}}} = \lim_{ u \to 0}{\frac{1}{x}\ln(1+u)^{\frac{1}{u}}} = \frac{1}{x} \\   
\end{align}$$
