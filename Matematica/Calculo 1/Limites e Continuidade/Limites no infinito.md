#math #calculo #limites 

**Definição 1.** Seja f uma função e suponhamos que exista a, tal que  $]a, +\infty[ \subset D_{f}$ , definimos
$$\lim_{x \to +\infty}{f(x)} = L \iff 
\begin{cases}
\forall\epsilon>0,\exists\delta > 0 \text{ com } \delta > a \text{ tal que}  \\
x < -\delta \implies L - \epsilon < f(x) < L + \epsilon
\end{cases}
$$
$$\lim_{x \to -\infty}{f(x)} = L \iff 
\begin{cases}
\forall\epsilon>0,\exists\delta > 0 \text{ com } -\delta < a \text{ tal que}  \\
x < -\delta \implies L - \epsilon < f(x) < L + \epsilon
\end{cases}
$$
### Exemplos de aplicação

**Exemplo 1.** Calcule $\lim_{x \to +\infty}{\frac{1}{x}}$ e justifique
Solução
Quanto maior o valor de x, mais próximo $\frac{1}{x}$ estará de 0 e, portanto
$$\lim_{x \to +\infty}{\frac{1}{x}} = 0$$
**Exemplo 2.** Calcule $\lim_{x \to +\infty}{\frac{1}{x^n}}$, no qual $n > 0, n \in \mathbb{N}$
Solução
$$\lim_{x \to +\infty}{\frac{1}{x^n}}= \lim_{x \to +\infty}{\left(\frac{1}{x}\right)^n}$$
Seja $u = \frac{1}{x}$. Como vimos no exemplo 1,$u \to 0$ quando $x \to +\infty$. Assim

$$\lim_{u \to 0}{u^n} = 0$$
Portanto,
$$\lim_{x \to +\infty}{\frac{1}{x^n}}= 0$$
**Exemplo 3**. Calcule $$\lim_{x \to +\infty}{\frac{x^5 + x^4 + 1}{2x^5 + x+ 1}}$$
Solução
$$
\begin{align}
\lim_{x \to +\infty}{\frac{x^5 + x^4 + 1}{2x^5 + x+ 1}} = \lim_{x \to +\infty}{\frac{x^5 \left( 1 + \frac{1}{x} + \frac{1}{x⁵} \right)}{x^5 \left( 2 + \frac{1}{x^4} + \frac{1}{x^5} \right)}} = \frac{1}{2}
\end{align}$$
