#computation #computer-science 

Um **sistema de numeração** define como  um número pode ser representado utilizando diferentes símbolos.

### Sistema de numerações posicionais
A posição que um símbolo ocupa determina o valor que ele representa. Neste sistema um número pode ser representado como:
$$\pm (S_{k-1} \dots S_{2}S_{1}S_{0}\cdot S_{-1}S_{-2}\dots S_{l})$$
Tem o valor(em decimal) de 
$$n = \pm S_{k-1} \cdot b^{k-1} + \dots+S_{1}\cdot b_{1}+ S_{0}\cdot b_{0} + S_{-1}\cdot b_{-1} + S_{-2}\cdot b_{-2} + \dots + S_{l} \cdot b^l$$

Onde S é conjunto de símbolos; b é a base(ou raiz), que é igual ao número de símbolos no conjunto S, e $S_{i}$ é o símbolo na posição $i$ .

### Sistema Decimal
Base (b) é igual a 10, e utiliza-se os símbolos (0,1,2,3,4,5,6,7,8,9) que chamamos habitualmente de "dígitos".

### Sistema Binário 
A base (b) é igual a 2, e S = (0,1). Os símbolos neste sistema são chamados de **dígitos binários** ou **bits**(Abrv. **B**inary **D**igits).

Por exemplo o número 2 em binário seria 10, o número 9 seria 1001.

**Convertendo um número por exemplo:** O número $(101,11)_{2}$ no sistema binário é igual ao número 5,75 e em decimal.

O sistema binário é amplamente utilizado nos computadores.

### Sistema Hexadecimal

Base é igual a 16, e os símbolos utilizados são (0,1,2,3,4,5,6,7,8,9, a,b,c,d,e,f).
onde a = 10, b = 11, c = 12, d = 13, e = 14, f = 15

Embora o sistema binário seja utilizado para o armazenamento de dados no computador, não é conveniente representar numéros fora do computador em binário, pois em binário ele, muitas vezes, ficam muito mais longos ao que correspondem em decimal. A sistema hexadecimal resolve esse problema.

### Número máximo (de acordo com k) em inteiro
$$N_{max} = 16^k - 1$$



