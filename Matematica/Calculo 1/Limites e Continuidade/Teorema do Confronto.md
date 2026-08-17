#math #calculo #limites 

**Teorema.** Sejam f,g e h três funções e suponhamos que exista r > 0, tal que

$$f(x) \leq g(x) \leq h(x)$$
Para $0 < |x - p| < r$. Nesta condições, se 
$$\lim_{ x \to p }{f(x)} = L \lim_{ x \to p }{h(x)} $$
então
$$\lim_{ x \to p }{g(x)} = L $$

### Exemplo de aplicação

Calcule o limite $$\lim_{x \to 0}{x²\sin \left(\frac{1}{x} \right)} $$
Sabemos que $$-1 \leq \sin \left( \frac{1}{x} \right) \leq 1$$
Agora multiplicamos os dois lados por $x²$
$$-x² \leq x²\sin\left(\frac{1}{x}\right) \leq x²$$
Assim,
	$$\lim_{x \to 0}{-x²} \leq \lim_{x \to 0}{x²\sin\left(\frac{1}{x}\right)} \leq \lim_{x \to 0}{x²}$$
Sendo 
$$0 \leq \lim_{x \to 0}x²\sin\left(\frac{1}{x}\right) \leq 0$$
Portanto, pelo teorema do confronto, 

$$\lim_{x \to 0}{x²\sin\left(\frac{1}{x}\right)} = 0$$

### Demonstração do Teorema do confronto

Como por hipótese, $$\lim_{ x \to p }{f(x)} = \lim_{ x \to p }{h(x)} $$
dado $\epsilon >  0$, existem $\delta_{1} > 0$ e $\delta_{2} > 0$ tais que 
$$\begin{cases} 
0 < |x-p| < \delta_{1} \implies L - \epsilon < f(x) < L +  \epsilon \\ \\
0 < |x-p| < \delta_{2} \implies L - \epsilon < h(x) < L +  \epsilon \\ \\
\end{cases}$$
Tomando-se $\delta=mín\{S_{1},S_{2}, r\}$

$$0 < |x-p| < \delta \implies L - \epsilon < f(x) \leq h(x) < L +  \epsilon$$
Logo
$$0 < |x-p| < \delta \implies L - \epsilon < g(x) < L +  \epsilon$$
Ou seja, 
$$\lim_{ x \to p }{g(x)} = L $$
 