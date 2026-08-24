#math #calculo #derivadas 

Seja $f$ derivável no intervalo aberto $I$ e seja $p$ um ponto de $I$ . A reta tangente em $(p, f(p))$ ao gráfico de $f$ é 
$$y-f(p)=f'(p)(x-p) \text{ ou } y=f(p)+f'(p)(x-p)$$
Deste modo, a reta tangente em $(p, f(p))$ é o gráfico da função $T$ dada por 
$$T(x) = f(p)+f'(p)(x-p)$$

**Definição 1.** Dizemos que $f$ tem concavidade para cima no intervalo aberto $I$ se
$f(x) > T(x)$
quaisquer que sejam $x$ e $p$ em $I$, com $x\neq p$.

**Definição 2.** Dizemos que $f$ tem concavidade para baixo no intervalo aberto $I$ se $f(x) < T(x)$ 
quaisquer que sejam $x$ e $p$ em $I$, com $x \neq p$ .

**Definição 3.** Sejam $f$ uma função e $p \in D_{f}$, com $f$ *contínua em p* . Dizemos que p é **ponto de inflexão de f** se existirem números reais $a$ e $b$ , com $p \in ]a,b[$, tal que $f$ tenha concavidades de "nomes" contrários em $]a,p[$ e em $]p,b[$ 

### Teorema
Seja $f$ uma função que admite derivada até a 2ª ordem(Leia [[Função derivada e derivadas de ordem superior | aqui]] ) no intervalo $I$ .
a) Se $f''(x) >0$ em $x \in I$, então $f$ terá concavidade para cima em $I$.
b) Se $f''(x) <0$ em $x \in I$, então $f$ terá concavidade para baixo em $I$

#### Exemplo 1.
Seja $f(x) = e^{-\frac{x²}{2}}$. Estude $f$ com relação à concavidade e determine os pontos de inflexão.

**Solução**
Primeiro vamos calcular as derivadas(de primeira e segunda ordem). ps: Por fim de teste, vou utilizar a [[Notações para a Derivada | notação de Leibniz]].
Seja $y = e^{-\frac{x²}{2}}$, temos
$$\frac{dy}{dx}=\frac{d}{dx} \left( e^{-\frac{x²}{2}} \right)$$
Sendo $u = -\frac{x²}{2}$, assim pela [[Regra da Cadeia para derivação de função composta | regra da cadeia]].
$$\frac{d}{dx} \left( e^{-\frac{x²}{2}} \right) = \frac{d}{du}\left( e^u\right) \cdot \frac{d}{dx}\left( -\frac{x²}{2} \right) = -xe^u$$
Unindo tudo, temos
$$\frac{dy}{dx}=-xe^{-\frac{x²}{2}}$$
Agora, vamos calcular a derivada de segunda ordem.
$$\frac{d²y}{dx²}
=\frac{d}{dx}\left( \frac{dy}{dx}\right)
=\frac{d}{dx}\left(-xe^{-\frac{x²}{2}}\right)$$
aplicando a [[Regras de derivação | regra do produto]]
$$\begin{align*} \frac{d}{dx}\left(-xe^{-\frac{x²}{2}}\right)
= \frac{d}{dx}(-x)'\left( e^{-\frac{x²}{2}} \right) + \frac{d}{dx}\left( e^{-\frac{x²}{2}}\right)(-x) \\
= -e^{-\frac{x²}{2}} + x²e^{-\frac{x²}{2}} \\
= (x² -1)e^{-\frac{x²}{2}}
\end{align*}$$
Portanto, 
$$\frac{d²y}{dx²}=(x²-1)e^{-\frac{x²}2{}}$$
Sabemos que $e^{-\frac{x²}{2}}>0$  para todo $x$ e, consequentemente, o sinal de $\frac{d²y}{dx}$ é o mesmo que $(x²-1)$. Logo, 
$$\begin{cases} 
 \frac{d²y}{dx} > 0 \text{ em } ]-\infty, -1[ \cup ]1, +]-\infty[ \\ 
 \frac{d²y}{dx} < 0 \text{ em } ]-1, 1[\\
\end{cases}$$