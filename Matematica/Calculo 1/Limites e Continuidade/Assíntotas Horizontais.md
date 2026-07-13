#math #calculo #limites  

-Assíntota horizontal ==é uma reta imaginária no plano cartesiano que indica o comportamento final de uma função==. Ela ocorre quando os valores da função (y) se aproximam cada vez mais de um valor constante específico à medida que a variável independente (x) cresce para valores muito altos positivos ou muito baixos negativos.

![[assintota-horizontal.png]]

A reta y = L é chamada assíntota horizontal da curva de y = f(x) se
$$\lim_{x \to +\infty}{f(x)} = L \text{ ou } \lim_{x \to -\infty}{
f(x)} = L $$

Relacionado diretamente a: [[Limites no infinito]].

#### Exemplo
Determine as assíntotas horizontais do gráfico da função $f(x) = \frac{\sqrt{2x² + 1}}{3x - 5}$

Solução
$$
\begin{align}
\lim_{x \to +\infty}{\frac{\sqrt{2x² + 1}}{3x - 5}} \\
&= \lim_{x \to +\infty}{\frac{\sqrt{x² (2 + \frac{1}{x²})}}{x(3 - \frac{5}{x}) }} \\
&= \lim_{x \to +\infty}\frac{\sqrt{x²}\sqrt{2 + \frac{1}{x²}}}{x(3 - \frac{5}{x})} \\
&= \lim_{x \to +\infty}{\frac{x\sqrt{2 + \frac{1}{x²}}}{x(3 - \frac{5}{x})}} \\
&= \lim_{x \to +\infty}{\frac{\sqrt{2 + \frac{1}{x²}}}{3 - \frac{5}{x}}} \\
&= \frac{\sqrt{2}}{3}
\end{align}
$$
Para $x \to -\infty$ temos o mesmo resultado absoluto, porém com valor negativo, uma vez que $\sqrt{x²} = |x|$ portanto para $x \to \infty$ temos $|x| = -x$.

Assim as assíntotas horizontais são $\frac{\sqrt{2}}{3}$ e $-\frac{\sqrt{2}}{3}$.
