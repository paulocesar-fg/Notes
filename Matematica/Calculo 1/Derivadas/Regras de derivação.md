#math #calculo #derivadas 

**Teorema 1.** Sejam f e g deriváveis em p e seja k uma constante . Então as seguintes funções são deriváveis em p e tôma-se:

D1)$(f+g)'(p) = f'(p)+g'(p)$
D2) $(kf)'(p) = k \cdot f'(p)$
D3) $(f \cdot g)'(p) = f'(p)g(p) + f(p)g'(p)$

**Demonstrações**

D1) 
$$\begin{align*}
(f+g)'(p) = \lim_{  x \to p}{\frac{[f(x)+g(x)]-[f(p) + g(p)]}{x-p}} 
\\= \lim_{ x \to p }{\left[  \frac{f(x) - f(p)}{x-p} + \frac{g(x) - g(p)}{x-p} \right]} 
\end{align*}$$
D2) $$\begin{align*}
(kf)'(p) =  \lim_{ x \to p }{\frac{kf(x) - kf(p)}{x-p}}
\\ = \lim_{ x \to p}{k \cdot \frac{f(x)-f(p)}{x-p}}
\\ =kf'(p)
\end{align*}$$
D3)$$\begin{align*}
(f \cdot g)'(p) = \lim_{ x \to p }{\frac{f(x)g(x)-f(p)g(p)}{x-p}} 
\\ =\lim_{ x \to p }{\frac{f(x)g(x) - f(p)g(p) + f(p)g(p) - f(p)g(p)}{x-p}}
\\=\lim_{ x \to p }{\left[ \frac{f(x)-f(p)}{x-p} \cdot g(x)+ f(x) \cdot \frac{g(x) - g(p)}{x-p}\right]} 
\end{align*}$$
**Teorema 2**.(Regra do quociente). Se f e g forem deriváveis em p e se $g(p) \neq 0$, então $\frac{f}{g}$ sendo derivável em p e 
$$D_{4})\left(\frac{f}{g}\right)'(p)= \frac{f'(p)g(p) - f(p)g'(p)}{[g(p)]^2}$$
**Demonstração**
D4) Seja $g(p) \neq 0$ , então
$$\left(\frac{f}{g}\right)'(p)=\lim_{ x \to p }{\frac{\frac{f(x)}{g(x)} - \frac{f(p)}{g(p)}}{x-p}} 
=\lim_{ x \to p }{\frac{f(x)g(p)-f(p)g(x)}{x-p}}\cdot \frac{1}{g(x)g(p)}
$$
Somando e subtraindo $f(p)g(p)$ ao numerador resulta
$$\left(\frac{f}{p}\right)'(p) = \lim_{ x \to p }{\left[\frac{f(x) - f(p)}{x-p} \cdot g(p)-f(p)\cdot \frac{g(x)-g(p)}{x-p}\right]} $$
E, portanto,
$$\left( \frac{f}{g}\right)'(p)=\frac{f'(p)g(p) - f(p)g'(p)}{[g(p)]^2}$$
