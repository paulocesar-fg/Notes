#math #logic #fme

É possível interligar proposições através de conectivos lógicos

## 1. Conectivo $\land$ 

Esse conectivo é chamado de **conjunção**. Uma proposição  composta $p \land q$ só é verdadeira quando ambas proposições p e q são verdadeiras; caso contrário, $p \land q$ é falso. 

Usa-se o símbolo $\land$ (em latex `\land`). Lê-se: "e" 

Tabela-verdade

| p   | q   | $p \land q$ |
| --- | --- | ----------- |
| V   | V   | V           |
| F   | V   | F           |
| V   | F   | F           |
| F   | F   | F           |

## 2. Conectivo $\lor$ 

Esse conectivo é chamado de **disjunção**. Uma proposição $p \lor q$ é verdadeira quando pelo uma das proposição é verdadeira; caso contrário, isto é, caso quando ambos sejam falsas, $p \lor q$ será falso.

Usa-se o símbolo $\lor$ (em latex `\lor`). Lê-se: "ou".

| p   | q   | $p \lor q$ |
| --- | --- | ---------- |
| V   | V   | V          |
| F   | V   | V          |
| V   | F   | V          |
| F   | F   | F          |

## 3. Conectivo $\implies$

Esse conectivo é chamado **bicondicional** . Uma proposição $p \implies q$  só é falsa caso p seja verdadeiro e q seja falso; caso contrário a condicional $p \implies q$  é verdadeira.

A primeira proposições p e q são denominas antecedente e consequente, respecivamente.

| p   | q   | $p \implies q$ |
| --- | --- | -------------- |
| V   | V   | V              |
| F   | V   | V              |
| V   | F   | F              |
| F   | F   | V              |

Usa-se o símbolo $\implies$ (em latex `\implies`).  $p \implies q$ lê-se: "Se p, então q".

#### 3.1 Relação de implicação

Dizemos que p implica q se não ocorrer que p seja verdadeiro e q seja falso, isto é, caso $p \implies q$ não seja falso. 

Obs: 

p implica q quando $p \implies q$  é verdadeiro
Todo teorema é uma implicação do tipo $\text{tese} \implies \text{hipótese}$ 

### 4. Bicondicional $\iff$

Esse conectivo é denominado **Bicondicional**. A bicondicional $p \iff q$ é verdadeira quando p e q possuem valores lógicos iguais; caso contrário, a bicondicional é falsa.

Tabela-verdade

| p   | q   | $p \iff q$ |
| --- | --- | ---------- |
| V   | V   | V          |
| F   | V   | F          |
| V   | F   | F          |
| F   | F   | V          |

Usa-se o símbolo $\iff$ (em latex `\iff`). Lê-se: "Se p, se e somente se, q" ou  "p  é condição suficiente e necessária para q".

#### 4.1 Relação de equivalência

Caso $p \iff q$ seja verdadeira, então dizemos que p é equivalente a q.

Obs: A bicondicional é uma condicional de "dois lados", isto é, quando:

$$ p \implies q \land q \implies p$$
