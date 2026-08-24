#math #calculo #derivadas 

Seja $f \text{ e } g$ duas funções tal que $$y = [f(x)]^{g(x)}$$
Quando precisarmos derivar funções deste tipo é recomendado usar a **derivação logarítmica**. Veja:

$$y = [f(x)]^{g(x)} \implies \ln y = \ln \left[ [f(x)]^{g(x)} \right] \implies \ln y = g(x)\ln[f(x)]$$
Agora vamos derivar os dois lados 
$$\begin{align*}
&(\ln y )' = [g(x)\ln [f(x)]]' \\ 
&\implies \frac{y'}{y}=g(x)'\ln[f(x)] + [\ln[f(x)]]'g(x) \text{(regra do produto)} \\
&\implies y'= y[g(x)'\ln[f(x)] + [\ln[f(x)]]'g(x)] \\
&\implies y'= [f(x)]^{g(x)}[g(x)'\ln[f(x)] + [\ln[f(x)]]'g(x)]
\end{align*}$$

 Portanto, 
 $$\frac{d}{dx}\left[ [f(x)]^{g(x)}\right] = [f(x)]^{g(x)}[g(x)'\ln[f(x)] + [\ln[f(x)]]'g(x)]$$

### Exemplo
Calcule $a) \frac{d}{dx}\left( x^x \right)$ 

**Solução**

$$\begin{align*}
&\frac{d}{dx}\left( x^x \right)=(x^x)[x'\ln x+[\ln x]'x]\text{(derivação logarítmica)} \\
&=(x^x)(\ln x+1)
\end{align*}$$

