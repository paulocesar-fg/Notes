#math #logic 

## Definition:

In mathematical logic, **laws** are universally valid rules that govern the behavior of logical statements and connectives.


#### De Morgan's laws

$$\neg (P \land Q) \iff \neg P \lor \neg Q$$
$$\neg (P \lor Q) \iff \neg P \land \neg Q$$

<hr>
#### Commutative laws

$$P \land Q \iff Q \land P$$
$$P \lor Q \iff Q \lor P$$
<hr>
#### Associative laws

$$P \land (Q \land R) \iff (P \land Q) \land R$$
$$P \lor (Q \lor R) \iff (P \lor Q) \lor R$$


<hr>
#### Idempotent laws
$$P \land P \iff P$$
$$P \lor P \iff P$$

<hr>

#### Distributive laws

$$P \land (Q \lor R) \iff (P \land Q) \lor (P\land R)$$
$$P \lor (Q \land R) \iff (P \lor Q) \land (P\lor R)$$

<hr>
#### Absorption laws 
 $$P \lor (P \lor Q) \iff P$$
 $$P \land (P \land Q) \iff P$$
 <hr>
#### Double Negation law

$$\neg\neg P \iff P$$

<hr>

#### Conditional laws

$$P \to Q \iff \neg P \lor Q$$
$$P \to Q \iff \neg(P \land \neg Q)$$
<hr>

#### Contrapositive law

$$P \to Q \iff \neg Q \to \neg P$$

#### Tautology Laws

[[Tautology and Contradiction | The Concept of the tautology]]

$$P \land \text{(a tautology)} \iff P$$
$$P \lor \text{(a tautology)} \to \text{(a tautology)}$$
$$\neg \text{(a tautology)} \to \text{a contradiction}$$

#### Contradiction laws

[[Tautology and Contradiction | The Concept of the contradiction]]

$$P \land Q \to \text{a contradiction}$$
$$P \lor \text{a contradiction} \iff P$$

$$\neg \text{(a contradiction)} \to \text{a tautology}$$

#### Quantifier Negation laws

$$\neg \exists P(x) \iff \forall x \neg P(x)$$
$$\neg \forall P(x) \iff \exists x \neg P(x)$$
