Alternating series/conditional convergence

Start with $a_1 = 1$
	Want $\displaystyle \sum_{n=1}^{\infty}(-1)^{n+1}a_n$ to diverge
		Condition $a_{n+1} \leq a_n$

Eg) $a_n = 8$
$\displaystyle \sum_{n=1}^{\infty}(-1)^{n+1}\cdot8$ does not converge
Tests:
1) Integral test
2) Divergence test
	(If $\displaystyle \lim_{n\to\infty}a_n \neq 0 \to \sum_{n=11}^{\infty}a_n$ diverges)

Alternating series test
If we have $(A_n)_{n=1}^{\infty}$:
1) $A_n \geq 0$
2) $A_{n+1} \leq A_{n}$
3) $\displaystyle \lim_{n\to\infty}A_n = 0$
Then $\displaystyle \sum_{n=1}^{\infty}(-1)^{n+1}A_n$ converges


If $\displaystyle \sum_{n=1}^{\infty}|a_n|$ converges, then $\displaystyle \sum_{n=1}^{\infty}a_n$ converges
However, converse is not true:
$\displaystyle \sum_{n=1}^{\infty}a_n$ converges,  but $\displaystyle \sum_{n=1}^{\infty}|a_n|$ diverges


Does $\displaystyle \sum_{n=1}^{\infty}(-1)^{n+1}\frac{1}{n}$ converge or diverge?
	By alternating series test, it converges

Def: If $\displaystyle \sum_{n=1}^{\infty}|a_n|$ converges, then we say $\displaystyle \sum_{n=1}^{\infty}a_n$ converges absolutely
If $\displaystyle \sum_{n=1}^{\infty}a_n$ converges but $\displaystyle \sum_{n=1}^{\infty}|a_n$ diverges, we say $\displaystyle \sum_{n=1}^{\infty}a_n$ converges conditionally

Eg.)
$\displaystyle (\frac{1}{1}- \frac{1}{2}) + (\frac{1}{3} - \frac{1}{4}) + (\frac{1}{5} - \frac{1}{6})+...$
but also
$\displaystyle (\frac{1}{1}-\frac{1}{2}-\frac{1}{4})+(\frac{1}{3}-\frac{1}{6}-\frac{1}{8})+...$
$\displaystyle = \frac{1}{4}+\frac{1}{3}(\frac{1}{2}-\frac{1}{4}) + ...$
