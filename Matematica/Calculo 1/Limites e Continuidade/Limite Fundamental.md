#math #calculo #limites 

## Teorema $$\lim_{ x \to 0 }{ \frac{\sin x}{x}} = 1$$
### Demonstração

**Propriedade 1**.  $\exists r > 0$ tal que
$$0 < \sin x < x < \tan g$$ ps: $\tan g = \frac{\sin x}{\cos x}$

Para  $0 < x < r$ Divindindo por $\sin x$
$$1 < \frac{x}{\sin x} < \frac{1}{\cos x}$$
Por outro lado,
$$-r < x < 0 \implies 0 < -x < r \implies \cos(-x) < \frac{\sin (-x)}{-x} < 1$$
Como $\cos(-x) = \cos x$ e $\frac{\sin (-x)}{-x}= \frac{\sin x}{x}$,
$$-r < x < 0 \implies \cos x < \frac{\sin x}{x} < 1$$
Como $$\lim_{ x \to 0 }{\cos x} = 1 = \lim_{ x \to 0 }{1}$$
Pelo teorema do confronto
$$\lim_{ x \to 0 }\frac{\sin x}{x} = 1$$