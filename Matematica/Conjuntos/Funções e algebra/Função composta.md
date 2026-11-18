#math #funcoes 

## Definição

A função composta é a aplicação de  [[Funções | função]] sobre o valor de outra função.
$$(g \circ f)(x) = g[f(x)] \text{ ou } h(x) = g[f(x)]$$
**o domínio de $h(x)$ é a imagem de $f(x)$**
$$D_{h} = IM_{f}$$
**Observações**
PS: A composta $g \circ f$ só está definida quando o contradomínio de f é igual ao domínio de g.
PS: Notemos que em geral $f \circ g \neq g \circ f$, isto é, a composição de funções não é comutativa.

### Associatividade da composição de funções
Quaisquer que sejam as funções tem-se
$$(h \circ g) \circ f = h \circ (g \circ f)$$

### Exemplos
1] $f(x) = x² + 4x -5$ e $g(x) = 2x - 3$
	a) Obtenha as leis que definem $f \circ g$ e $g \circ f$.

a) 
$$\begin{flalign*}
& \text{Para } (f \circ g)(x) \text{ temos } \\
&(f \circ g)(x) = f[g(x)] = (2x - 3)² + 4(2x - 3) - 5 \\ 
& = 4x² - 12x + 9 + 8x - 12 - 5 \\ 
&= 4x² -4x -8 \\
& \text{Assim, } (f \circ g)(x) = 4x² -4x - 8 \\
\\
\\
&\text{Para } (g \circ f)(x) \text{ temos } \\
&(g \circ f)(x) = g[f(x)] = 2(x² + 4x - 5) - 3 \\
&=2x² + 8x - 13 \\
&\text{Portanto, } (g \circ f)(x) = 2x² + 8x - 13
\end{flalign*}$$

2] Sejam as funções reais $f(x) = 3x - 5$ e $(f \circ g)(x) = x² - 3$. Determine a lei da função $g$
$$\begin{flalign*}
&(f \circ g)(x) = f(g(x)) \text{ e seja } y = g(x) \\
& x²-3 = f[g(x)] \implies x²-3=3y - 5 \implies y = \frac{{x²+2}}{3}\\
&\text{Portanto, } g(x) = \frac{{x^2+2}}{3}
\end{flalign*}$$

