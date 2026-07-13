#math #calculo #limites 

Sejam f uma função, p um número real e suponhamos que existge b tal que $]p, b[ \subset D_{f}$  , Definimos
$$\lim_{ x \to p⁺ }{f(x)} = L \iff \begin{cases}
\forall \epsilon > 0, \exists \delta >0 \text{ tal que}  \\
p < x < p + \delta \implies | f(x) - L| < \epsilon
	
\end{cases}
$$

O número L, quando existe, denomina-se limite lateral à **direita** de f em p.

Suponhamos agora que exista um número real a tal que $]a, p[ \subset D_{f}$  definimos
$$\lim_{ x \to p^- }{f(x)} = L \iff \begin{cases}
\forall \epsilon > 0, \exists \delta >0 \text{ tal que}  \\
p - \delta < x < p \implies | f(x) - L| < \epsilon
	
\end{cases}
$$

O número L, quando existe, denomina-se limite lateral à **esquerda** de f em p.

### Existência do Limite bilateral

**Teorema.** Seja f uma função, e p um número real e suponha-se que exista a e b tais que $]a, p[ \subset D_{f}$ e $]p, b[ \subset D_{f}$, Então

$$\lim_{ x \to p^+}{f(x)} = \lim_{ x \to p^- }{f(x)} = L \implies \exists \lim_{ x \to p }{f(x)} = L  $$

De forma equivalente, se o limite lateral à  esquerda de f em p for diferente do limite lateral a direita de p, então o limite de f quando x tende a p não existe.

