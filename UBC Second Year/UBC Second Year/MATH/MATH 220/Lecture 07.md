Quantifiers

Universal Quantifier $\forall$ (for all, for every, for any)
	To prove a statement of the form $\forall x\in A, P(x)$, we must prove that $P(x)$ is true for every $x\in A$

Existential quantifier $\exists$ (there exists, there is, there is at least one).
	Usually followed by "such that"
	To prove a statement of the form $\exists x\in A, P(x)$, we need to exhibit ***one*** $x\in A$ such that $P(x)$ is true

We call $A$ the domain of the quantifier

Sentences of the forms above are always statements

Combining quantifiers
Very often, we combine quantifiers to form more complicated statements
	Consider the statement $P$
		$\forall x \in\mathbb{R}, \exists y\in\mathbb{R}$ such that $x+y=0$
			$P$ is true because given an arbitrary $x\in\mathbb{R}$, we can take $y = -x$ and then $x+y=x+(-x) = 0$
	Now consider the statement Q:
		$\exists y \in\mathbb{R}$ such that $\forall x\in\mathbb{R}, x + y = 0$
			$Q$ is false because for any $y\in\mathbb{R}$, it cannot happen that $x+y = 0$ for every $x \in R$.
				For example, for an arbitrary $y\in\mathbb{R}$, if we take $x = 1-y$, then
					$x + y = (1-y) + y = 1 \neq 0$

