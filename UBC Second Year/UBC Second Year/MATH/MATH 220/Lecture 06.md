Separate scratch work from the final proof
Write in complete sentences, using words, and not just mathematical symbols
If you're proving an implication $P\implies Q$, start by assuming $P$ is true and then deduce through a series of valid mathematical/logical operations that $Q$ is true
In scratch work, sometimes it's easier to work backwords from $Q$ to $P$ (this is often the case when proving inequalities), but in the final proof, you must work forwards from $P$ to $Q$
Be careful about distinguishing $P\implies Q$ from $Q \implies P$

Two statements $P$ and $Q$ are equivalent if $P \Leftrightarrow Q$ is a tautology ( a tautology is a true statement).
	We write $P \equiv Q$
	$P \equiv Q$ if and only if they are both true or false
	$P \equiv Q$ if and only if they have the same truth table

| Double Negation  | $sim(\sim P) \equiv P$                                         |
| ---------------- | -------------------------------------------------------------- |
| Implication      | $(P\implies Q)\equiv (\sim P) \lor Q$                          |
| Biconditional    | $(P \Leftrightarrow Q \equiv (P\implies Q) \land (Q\implies P$ |
| De Morgan's Laws | $\sim(P\lor Q)\equiv(\sim P)\land (\sim Q)$                    |
|                  | $\sim(P\land Q)\equiv (\sim P)\lor (\sim Q)$                   |
| Exclusive Or     | $(P$ XOR $Q) \equiv (P\land\sim Q) \lor (\sim P \land Q)$                      |

