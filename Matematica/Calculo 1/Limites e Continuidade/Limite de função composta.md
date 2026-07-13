#math #calculo #limites 

Sejam f e g duas funções tais que $\mathrm{Im}_{f} \subset D_{g}$, isto é, $\mathrm{Im}_{f} = \{f(x) | x \in D_{f}\} \subset D_{g}$ . Assim:
$$\lim_{ x \to p }{g(f(x))} $$
Supondo que $$\lim_{ x \to p }{f(x)} = a $$
podemos tomar $u = f(x), x \in D_{f}$ . Assim:
$$\lim_{ x \to p }{g(f(x))} = \lim_{ u \to a }{g(u)}\text{ sendo } u = f(x), x \in D_{f} \text{ e } a=\lim_{ x \to p }{f(x)} $$

#### Exemplo:

Calcule o Limite $$\lim_{ x \to 0 }{\frac{1 - \cos (\sin x)}{x²}}$$
Solução
$$\lim_{ x \to 0 }{\frac{1 - \cos (\sin x)}{x²}} = \lim_{ x \to 0 }{\frac{1 - \cos (\sin x)}{(\sin x)²}} \cdot \left( \frac{\sin x}{x} \right)²$$
Calculemos os dois limites separadamente. 

Seja $u = \sin x$, $u \to 0$ quando $x \to 0$, assim podemos rescrever o primeiro limite como
$$\lim_{ u \to 0 }{\frac{1 - \cos u}{u²}} = \frac{1}{2}$$
(obtemos um limite fundamental)

O segundo limite obtido também é um limite fundamental 
$$\lim_{ x \to 0}{\left( \frac{\sin x}{x} \right)²} = \lim_{ x \to 0}{\left( \frac{\sin x}{x} \right)} \cdot \lim_{ x \to 0}{\left( \frac{\sin x}{x} \right)}   = 1$$
Portanto, 
$$\lim_{ x \to 0 }{\frac{1 - \cos (\sin x)}{x²}}= \frac{1}{2}$$
