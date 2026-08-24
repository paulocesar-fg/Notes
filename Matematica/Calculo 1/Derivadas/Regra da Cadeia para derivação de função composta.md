#math #calculo #derivadas 

Seja $y=f(g(x))$, onde $\mathrm{Im} \subset \mathrm{D_{f}}$ . Pode-se calcular a derivada 
$$\begin{align*}
\frac{dy}{dx}=\lim_{ \Delta x \to 0 }{\frac{f(g(x + \Delta x))-f(g(x))}{\Delta x}} 

= \lim_{ \Delta x \to 0 }{ \frac{f(g(x + \Delta x))-f(g(x))}{g(x+\Delta x)-g(x)}}
\cdot \frac{g(x + \Delta x)-g(x)}{\Delta x}
\end{align*}$$
Seja $u=g(x)$ e $\Delta u=g(x+\Delta x)-g(x)$, Temos
$$\lim_{ \Delta x \to 0 }{\frac{f(g(x+\Delta x))-f(g(x))}{g(x+\Delta x)-g(x)}}=\lim_{ \Delta u \to 0 }{\frac{f(u + \Delta u)-f(u)}{\Delta u}}=\frac{dy}{du}
$$
Além disso, sabe-se que
$$\lim_{ \Delta x \to 0 }{\frac{g(x+\Delta x)-g(x)}{\Delta x}}=\lim_{ \Delta x \to 0 }{\frac{\Delta u}{\Delta x}}=\frac{du}{dx} $$
Unindo tudo, temos
$$\frac{dy}{dx}=\frac{dy}{du}\cdot \frac{du}{dx}$$
Em que $\frac{dy}{du}$ deve ser calculado em $u=g(x)$.

**PS:** Em outra notação, sendo $h(t)=f(g(t)),x=g(t) \text{ e } y=f(x)$.
$$h'(t)=f'(g(t))g'(t), t \in D_{g}$$

### Exemplos
a) $y=e^{3x}$ 

$y=e^{3x}$ , em que $u=3x$, pela regra da cadeia
$$\frac{dy}{dx}=\frac{dy}{du} \cdot \frac{du}{dx}$$
Como $\frac{dy}{du} = e^u$ e $\frac{du}{dx}=3$, resulta
$$\frac{dy}{dx}=3e^u=3e^{3x}$$
b) $y=\sin t^²$.
$y=\sin u$ , sendo $u=t^2$ , Assim
$$\frac{dy}{du}=\cos u \text{ ou } \frac{du}{dt}=2t$$
Logo,
$$\frac{dy}{dx}=2t\cos u=2t\cos t²$$
Em outra notação, teriamos
$$\frac{dy}{dt}=[\sin t²]'=\sin't²(t²)'=2t\cos t²$$
c) $f(x)=(3x² + 1)³$, calcule a derivada de f
$u=3x²+1$ assim, 
$$\frac{dy}{dx}= \frac{dy}{du} \cdot \frac{du}{dx} \text{ ou } f'(x)=(u³)'(u)'$$
Sendo $$\begin{cases}  
\frac{du}{dx}=(3x²)' + (1)' = 6x  \\
\frac{dy}{du}=(u^3)'=3u²=3(3x²+1)² \\
\end{cases}$$
Portanto, 
$$\frac{dy}{dx}=6x \cdot 3(3x²+1)²=18x(3x²+1)²$$
