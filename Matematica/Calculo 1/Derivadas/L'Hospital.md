#math #calculo #derivadas 

A regra de L'Hopital aplica-se a cálculo de [[Definição de Limite | limites]] que apresentam indeterminações dos tipos $\frac{0}{0}$ e $\frac{\infty}{\infty}$ .

### 1ª Regra de L'Hospital
Sejam $f \text{ e } g$ deriváveis em $]p-r,p[$ e em $]p, p+r[(r>0)$ , com $g'(x) \neq 0$ para $0<|x-p|<r$.
Nestas condições, se 
$$\lim_{ x \to p }{f(x)} = 0 \text{ e } \lim_{ x \to p }{g(x)} = 0 $$
e se $\lim_{ x \to p }{\frac{f'(x)}{g'(x)}}$ existir(finito ou infinito), então $\lim_{ x \to p }{\frac{f(x)}{g(x)}}$ existirá e 
$$\lim_{ x \to p }{\frac{f(x)}{g(x)}} = \lim_{ x \to p }{\frac{f'(x)}{g'(x)}}$$
Observamos que a regra de L'Hospital contínua válida se substituirmos $x \to p⁺$ por $x \to p⁻$ ou por  $x \to \pm \infty$.

### 2ª Regra de L'Hospital
Sejam $f \text{ e } g$ deriváveis em $]m, p[$ com $g'(x)\neq 0$ em $]m, p[$.
$$\lim_{ x \to p⁻ }{f(x)=+\infty} \text{ e } \lim_{ x \to p⁻ }{g(x)=+\infty} $$
e se $\lim_{ x \to p }{\frac{f'(x)}{g'(x)}}$ existir(finito ou infinito) então $\lim_{ x \to p⁻ }{\frac{f(x)}{g(x)}}$ existirá e 
 $$\lim_{ x \to p⁻ }{\frac{f(x)}{g(x)}} = \lim_{ x \to p⁻ }{\frac{f'(x)}{g'(x)}}$$

### Exemplos
$$a)\lim_{ x \to 1 }{\frac{x⁵-6x³+8x-3}{x⁴-1}} $$
**Solução**
$$\lim_{ x \to 1 }{\frac{x⁵-6x³+8x -3}{x⁴-1}}=\left[ \frac{0}{0} \right]$$
Aplicando a 1ª regra de L'Hospital.
$$\lim_{ x \to 1 }{\frac{(x^5-6x³+8x-3)'}{(x^{4}-1)'}}=\lim_{ x \to 1 }{\frac{5x⁴-18x²+8}{4x³}} = \frac{-5}{4}$$
<hr>

$$b) \lim_{ x \to \infty }{\frac{e^x}{x}} $$
**Solução**

$$\lim_{ x \to \infty } {\frac{e^x}{x}}=\left[ \frac{\infty }{\infty} \right]$$
Aplicando a 2ª regra de L'Hospital
$$\lim_{ x \to \infty } {\frac{(e^x)'}{(x)'}}=\lim_{ x \to \infty } {e^x}=+\infty$$

<hr>

$$c) \lim_{ x \to 0^+}{{x \ln x}} $$
**Solução**
$$\lim_{ x \to 0⁺ }{x \ln x} = [0 \cdot (-\infty)]$$
Que é uma indeterminação, que  pode ser colocada na forma $\frac{0}{0}$ ou $\frac{\infty}{\infty}$. E passando para $\frac{\infty}{\infty}$ pode-se eliminar o $\infty$.
$$\lim_{ x \to 0^+ }{x \ln x} = \lim_{ x \to 0⁺ }{\frac{\ln x}{\frac{1}{x}}}=\left[ \frac{-\infty}{\infty} \right]$$
Aplicando a 2ª regra de L'Hospital temos
$$\lim_{ x \to 0+ }{\frac{(\ln x)'}{\left( \frac{1}{x} \right)'}} = \lim_{ x \to 0⁺ }{\frac{\frac{1}{x}}{\frac{-1}{x²}}} = \lim_{ x \to 0⁺ }{-\frac{x²}{x}}=\lim_{ x \to 0⁺ }{(-x)} = 0   $$
