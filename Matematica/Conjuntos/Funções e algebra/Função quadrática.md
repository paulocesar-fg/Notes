#math #funcoes 

## Definição 
Uma aplicação(função) de $f$ de $\mathbb{R} \text{ em } \mathbb{R}$ recebe o nome de **função quadrática** ou do **2º grau** , quando associa a cada $x \in \mathbb{R}$ o elemento $(ax² + bx + c) \in \mathbb{R}$, em que $a,b \text{ e } c \in  \mathbb{R}$ e $a \neq 0$.
$$f(x) = ax² + bx+ c, \text{ com } a \neq 0$$
Onde:
$a$ = coeficiente angular;
$b$ = coeficiente linear;
$c$ = termo indenpendente;

**obs:** Para entender e manipular funções quadráticas e recomendado o conhecimento das propriedades das equações e inequações do 2º grau.

### Zeros 
Os zeros da função quadrática $f(x) = ax² + bx + c$ são os valores  reais tais que $f(x)=0$ e, portanto, as soluções da equação do 2º grau:

$$ax² + bx +c = 0, \text{ tal que } x = \frac{-b \pm \sqrt{ \Delta}}{2a}, \text{ onde } \Delta = b² -4ac$$
#### Demonstração da fórmula quadrática
Seja a equação $$ax² + bx + c = 0 , \text{ sendo } a \neq 0$$
Atraves do *princípio da igualdade* podemos manipular essa expressão
$$\begin{flalign*} \\
&ax² + bx + c = 0  \\
&\iff  x² + \frac{b}{a}x + \frac{c}{a} = 0 \\
 &\iff x² + \frac{b}{a}x = - \frac{c}{a}
\end{flalign*}$$
Agora, vamos *completar o quadrado*; sabe-se que $(x + y)² = x² + 2xy + y²$,   tomemos $\frac{b}{a}x$ como $2xy$ assim temos $2xy = \frac{b}{a}x \iff y = \frac{b}{2a}$. Assim, podemos adicionar aos dois membros da primeira expressão
$$\begin{flalign*}
& x² + \frac{b}{a}x + \left(\frac{b}{2a}\right)² = \left(\frac{b}{2a}\right)² - \frac{c}{a} \\
& \iff \left(x + \frac{b}{2a}\right)² = \frac{b²}{4a²} - \frac{c}{a} \\
&\iff \sqrt{ \left(x + \frac{b}{2a}\right)²} = \sqrt{   \frac{b² - 4ac}{4a²} } \\
&\iff x + \frac{b}{2a} = \frac{\pm \sqrt{ b² - 4ac }}{2a} \\
&\iff x = \frac{-b \pm{\sqrt{b²-4ac }}}{2a} \\
&\iff x = \frac{-b \pm{\sqrt{\Delta}}}{2a}, \text{ com } \Delta = b² - 4ac \\
\end{flalign*}$$

### Concavidade 
O gráfico da função quadrática é uma parábola de concavidade voltada para cima ou para baixo. 

Se $a > 0$ concavidade para cima
Se $a < 0$ concavidade para baixo

### Forma canônica
$$f(x) = a\left[ \left( x + \frac{b}{2a} \right)² - \frac{\Delta}{4a²} \right]$$
### Número de raízes (zeros)
$$ax² + bx + c = 0 \iff 
\begin{cases} 
\Delta> 0 \implies x = \frac{- b+\sqrt{ \Delta }}{2a} \lor  \frac{x = -b - \sqrt{ \Delta }}{2a} \\
\Delta = 0 \implies x = -\frac{b}{2a} \text{ (uma raiz)} \\
\Delta < 0 \implies \text{ Não existem raízes reais}(\sqrt{\Delta } \not\in \mathbb{R})
\end{cases} 
$$
### Relações de Girard

Seja r1 e r2 duas raízes distintas de $ax² + bx + c$

**Teorema.**
$$\begin{cases} 
 r_{1} + r_{2} = -\frac{b}{a} \\
 r_{1}r_{2}  = \frac{c}{a}
\end{cases}$$
### Máximo e Mínimo

$P(x_{v}, y_{v})$ é Ponto máximo( $a < 0$) ou Ponto Mínimo($a > 0$) se
$$\begin{cases} 
x_{v} = \frac{-b}{2a} \\
y_{v} =  \frac{-\Delta}{4a}
\end{cases}$$
### Eixo de simetria
O gráfico função quadrátca admite um eixo de simetria perpendicular ao eixo dos x e que passa pelo vértice.

Para provar a existência do eixo de simetria é necessário provar que, dado um ponto $A\left( -\frac{b}{2a} -r, y\right)$,  com $r \in \mathbb{R}$, pertencente ao gráfico da função, existe $B\left( -\frac{b}{2a} +r, y \right)$ também pertencente ao gráfico da função.
