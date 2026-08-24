#math #calculo #derivadas 

Como consequência do [[Teorema do valor médio(TVM) | TVM]] temos o seguinte teorema.

### Teorema

**Teorema.** Seja $f$ contínua no intervalo $I$ .
a) Se $f'(x)>0$, para todo $x \in I$, então $f$ será **estritamente crescente** em $I$
b) S e $f'(x)<0$, para todo $x \in I$, então $f$ será **estritamente decrescente** em $I$

### Demonstrações

**Demonstração**
a) Sejam $s, t \in I$, com $s < t$.
Como $f$ é derivável em $I$ , ela é contínua em $[s,t]$ (Veja [[Derivabilidade e Continuidade]]). Assim, pelo [[Teorema do valor médio(TVM) | Teorema do Valor Médio]] , existe um ponto $\overline{x} \in ]s,t[$ tal que $$1)f'(\overline{x})=\frac{f(t)-f(s)}{t-s}$$
Pela hipótese $f'(\overline{x}) > 0$. E , sendo $s < t$ então $t-s>0$.
Multiplicamos ambos os lados da igualdade (1) por $t-s$ temos
$$f(t)-f(s)=f'(\overline{x})(t-s)$$
Como sabemos que $f'(\overline{x})>0$ e que $t-s>0$. Então $f'(x)(t-s) > 0$, dessa forma concluí-se que 
$$f(t)-f(s)>0 \implies f(s) < f(t)$$
Portanto, $$\forall s, t \in I, s<t \implies f(s)<f(t) \text{ , isto é, estritamente crescente}$$
b) Sejam $s,t \in I$, com $s < t$.
Como $f$ é derivável em $I$, logo ela é contínua em $[s,t]$(Veja [[Derivabilidade e Continuidade]]).
Assim, pelo [[Teorema do valor médio(TVM) | Teorema do Valor Médio]] , existe um ponto $\overline{x} \in ]s,t[$ tal que
$$f(t)-f(s)=f'(\overline{x})(t-s)$$
Por hipótese, $f'(\overline{x})< 0$, e como $s<t$ então $t-s>0$. Então $f'(\overline{x})(t-s)<0$, dessa forma concluí-se que 
$$f(t)-f(s)<0 \implies f(s) > f(t)$$
Portanto,
$$\forall s, t \in I, s<t \implies f(s) > f(t) \text{ , isto é, estritamente decrescente.}$$

### Exemplos
EX 1) Determine os intervalos de crescimento e de decrescimento de $f(x) = x³-2x²+x+2$. Esboce o gráfico

$$\begin{align*}
f'(x)=(x³)' - 2(x²)' + (x)' + (2)'
\\=3x²-4x+1
\end{align*}$$
Assim, f'(x) é uma equação do 2° grau. As raízes de $f'(x)$ são dados por $R = \left\{  1, \frac{1}{3}  \right\}$. Esboçando o gráfico da derivada de  $f'(x)$ temos:

![[grafico-derivada-segundo-grau.png]]

Sendo Assim,
$$\begin{cases} 
x \in ]-\infty, \frac{1}{3}[ \cup  ]1, +\infty[ \implies f'(x) > 0 \\ \\
x \in \left[ \frac{1}{3},1 \implies f'(x) < 0 \right]
\end{cases}$$
Logo,
$$\begin{cases}  
 f \text{ é estritamente crescente em } ]-\infty, \frac{1}{3}[ \cup ]1,+\infty[ \\ \\
 f \text{ é estritamente decrescente em } \left[ \frac{1}{3},1 \right]
\end{cases}$$

Agora vamos calcular as [[Assíntotas Horizontais]], isto é, os limites para $x \to +\infty$ e $x \to -\infty$.
$$\lim_{ x \to +\infty }{x³-2x²+x+2} = \lim_{ x \to +\infty }{x³\left( 1 - \frac{2}{x} + \frac{1}{x²} + \frac{2}{x³}\right)} = +\infty  $$
$$\lim_{ x \to -\infty }{x³-2x²+x+2} = \lim_{ x \to -\infty }{x³\left( 1 - \frac{2}{x} + \frac{1}{x²} + \frac{2}{x³}\right)} = -\infty  $$

Assim,

| x   | f(x)  |
| --- | ----- |
| -1  | -2    |
| 0   | 2<br> |
| 1   | 2     |
| 1/3 | 58/27 |
![[grafico-variacao-de-crescimente-e-decrescimento-da-funcao.png]]