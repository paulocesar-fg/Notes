#math #calculo #limites

### Definição intuitiva

Seja *f* uma função, e *a* um ponto qualquer. Observe a seguinte notação:
$$\lim_{ x \to a}{f(x)} = L $$
Lê-se: O limite de *f*, quando *x* tende a *a*, é *L*.
**Intuitivamente**, isso quer dizer quer quando o valor de x se aproxima do valor de a, o valor de f(x) se aproxima de L.

### Definição Formal

$$\lim_{ x \to p}{f(x)}=L \iff \begin{cases}
\forall \epsilon > 0, \exists \delta>0\text{(dependendo de epsilon) tal que} \\ \\
0 < |x -p| < \delta \implies |f(x) - L| < \epsilon \\
\end{cases}
$$
**Observações:**
*f* não precisa estar definida em p.
L pode ser diferente de f(p)
Se L = f(p) então a função é continua.

### Exemplos:

**a) Calcule $\lim_{ x \to 2 }{2x + 4}$.**
Como não a indefinição para x = 2, podemos apenas substituir o valor de x por 2. Dessa forma, $$\lim_{ x \to 2 }{2x + 4}= 8$$
**b)** Calcule $\lim_{ x \to 1 }{\frac{x-1}{x² - 1}}$
Perceba que há uma indeterminação, pois ao substituir x por 1, obtemos 0 no denominador. Em casos como esse, precisamos contornar a indeterminação antes de calcular o limite. Neste caso, $$\lim_{ x \to 1 }{\frac{x-1}{x² - 1}} = \lim_{ x \to 1 }{\frac{x-1}{(x - 1)(x+1)}}=\lim_{ x \to 1 }{\frac{1}{x+1}} = \frac{1}{2}$$

