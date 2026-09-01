#math #inequacoes 

## Inequação equivalente

Duas inequações são equivalentes em $D \subset \mathbb{R}$ se o **conjunto solução da primeira é igual ao conjunto solução da segunda**.

EX: $3x+6>0 \text{ e } x+2>0$, pois em $\mathbb{R} S= \{ x \in \mathbb{R} |x > -2 \}$ para ambas.

### Princípios de equivalência

**P1)** Sejam f(x) e g(x) definidas em $D_{1} \text{ e } D_{2}$ respectivamente. Se a função h(x) é definida em $D_{1} \cap D_{2}$, as inequações
$$f(x)<g(x) \iff f(x)+h(x)<g(x)+h(x)$$
Exemplo: $3x-1 : 2x +3$
Seja $h(x) = -2x +1$
$$(3x-1) + (-2x+1) < (2x+3) +(-2x+1) \iff x>4$$
Além disso, pode-se transpor um termo "trocando o sinal" pela propriedade P1.
$$f(x)+h(x) < g(x) \implies f(x) < g(x) - h(x)$$

**P2)** Sejam as funções f(x) e g(x) definidas em $D_{1} \text{ e } D_{2}$ respectivamente. Se a função h(x) é definida em $D_{1} \cap D_{2}$ e tem sinal constante, então

a) Se $h(x)>0,$
$$ f(x)<g(x) \iff f(x)\cdot h(x) < g(x)\cdot h(x) $$

b) Se $h(x) < 0$(Inversão de sinal)
$$f(x)<g(x) \iff f(x)\cdot h(x) > g(x)\cdot h(x)$$

**EXEMPLOS**

a) Resolva a inequação $\frac{3x-2}{1-x} \leq -3$ .

$$\begin{align*} 
& \frac{3x-2}{1-x}\leq -3 \iff \frac{3x-2}{1-x}+3\leq 0 
 \iff \frac{3x-2 + 3(1-x)}{1-x}
 \leq 0 \\ 
 &\iff \frac{3x-2+3-3x}{1-x} \leq 0 \iff \frac{1}{1-x} \leq 0, \text{ Assim,} \\
 & 1-x <0 \iff -x < -1 \iff x>1 \\
 \\
 & \text{Portanto,} \\
 & S = \{ x \in \mathbb{R} | x > 1 \} \text{ ou } S = ]1, + \infty[
\end{align*}$$
