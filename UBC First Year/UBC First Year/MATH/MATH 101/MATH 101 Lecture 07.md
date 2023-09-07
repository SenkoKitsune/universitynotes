Improper integrals
	improper integrals are definite integrals
	Δx = $\displaystyle\frac{b-a}{n}$
		doesn't make sense if $b = +\infty$ or $a = -\infty$
		Definite integrals are called improper integrals

Eg) What is $\displaystyle \int_{-1}^{1}\frac{1}{x^2}dx$
	FTC: $\displaystyle\frac{x^{-1}}{-1} |_{-1}^{1} = -2$
	FTC does not apply because $\displaystyle\frac{1}{x^2}$ is not continuous at 0
		vertical asymptote
	Answer: We don't know how to do it

Method:
	Use limits (replace any infinite quantity by the appropriate limit)
	Convergence and divergence
		Improper integrals are computed using limits
			limits may exist (equals a number) or not (infinite, oscillate, etc)
		Improper integrals converge is the limit exists as a number
		Improper integrals diverges by oscillating, to $+\infty$ or to $-\infty$, etc

Eg) $\displaystyle\int_{0}^{\infty}e^{-x}dx$
$e^{-x} > 0$
Bounding region is infinite, area may be finite or infinite

Replace $\infty$ with a limit
$\displaystyle\int_{0}^{\infty}e^{-x}dx = \lim_{R\to\infty}\int_{0}^{R}e^{-x}dx$
Solve with FTC, then take the limit
	$\displaystyle\lim_{R\to\infty}1-\frac{1}{e^R}$
	= 1
	integral converges to 1

Given a real number a and a real-valued function f defined on $[a, +\infty)$, we define
	$\displaystyle\int_{a}^{\infty}f(x)dx = \lim_{R\to\infty}\int_{a}^{R}f(x)dx$

Given a real number b and real-valued function f defined on $(-\infty, b]$, we define
	$\displaystyle\int_{-\infty}^{b}f(x)dx = \lim_{R\to -\infty}\int_{R}^{b}f(x)dx$

The doubly-improper integral $\displaystyle\int_{-\infty}^{\infty}f(x)dx$
	$\displaystyle\int_{-\infty}^{\infty}f(x)dx = \int_{-\infty}^{0}f(x)dx+\int_{0}^{\infty}f(x)dx$
	$\displaystyle\lim_{R_1\to -\infty}\int_{R_1}^{0}f(x)dx+\lim_{R_2\to\infty}\int_{0}^{R_2}f(x)dx$
	converges if and only if both limits on the right exist (Note the independence of $R_1$ and $R_2$)

Unbounded Integrand
eg) Find $\displaystyle\int_{0}^{4}\frac{1}{x}dx$
	$\displaystyle\frac{1}{x}\to\infty$ as $\displaystyle x \to \infty$
	$\displaystyle\int_{0}^{4}\frac{1}{x}dx = \lim_{C\to 0^+}\int_{C}^{4}dx = ln|x| |_C^4 = ln4 - lnC = ln4 - (-\infty) = +\infty$
	Integral diverges to $+\infty$
		Area is infinite

Infinite Integrand
If f is continuous on $[a, b)$ but not at b, we define
$\displaystyle \int_{a}^{b}f(x)dx = \lim_{t\to b^-}\int_{a}^{t}f(x)dx$

If f is continuous on $(a, b]$ but not at a, we define
$\displaystyle \int_{a}^{b}f(x)dx = \lim_{s\to a^+}\int_{s}^{b}f(x)dx$

If f is continuous on $[a, c) \cup (c, b]$ but not at $\displaystyle c \in (a, b)$, 
$\displaystyle \int_{a}^{b}f(x)dx = \displaystyle \int_{a}^{c}f(x)dx + \displaystyle \int_{c}^{b}f(x)dx = \lim_{t\to c^-}\int_{a}^{t}f(x)dx + \lim_{s\to c^+}\int_{s}^{b}f(x)dx$ 


Eg) Find all the values of the constant $p \in R$ for which $\displaystyle \int_{0}^{1}x^pdx$ diverges
	If $P \geq 0 \to x^p$ continuous function $\to$ proper integral $\to$ converges
	If $P < 0 \to x^p = \displaystyle\frac{1}{x^p}$ discontinuous at 0 (vertical asymptote)
		$\displaystyle \int_{0}^{1}x^pdx = \lim_{c\to 0^+}x^pdx$
			$\displaystyle p = -1 \to log|x| |_c^1 = 0 - log(c) = -\infty$
				diverges
			$\displaystyle p \neq -1 \to \frac{x^{p+1}}{p+1}|_c^1 = 1 - c^{p+1}$
				$p + 1 > 0 \to 1 - 0 = 1$
					converges
				$p + 1 < 0 \to +\infty$
	Converges if $p > -1$
	Diverges if $p \leq -1$


Eg) does $\displaystyle \int_{-1}^{1}\frac{1}{x^2}dx$ converge or diverge
	=$\displaystyle \int_{-1}^{0}\frac{1}{x^2}dx + \int_{0}^{1}\frac{1}{x^2}dx$
		$\displaystyle \int_{0}^{1}\frac{1}{x^2}dx \to P = -2$
			diverges
			If one diverges, the integral diverges

Eg) Find all the values of the constant $p \in R$ for which $\displaystyle \int_{1}^{\infty}x^pdx$ converges
	$\displaystyle \int_{1}{\infty}x^pdx = \lim_{R\to\infty}\int_{1}^{R}x^pdx$
		$p = -1 \to log(R)-log(1) \to =\infty$
			diverges
		$\displaystyle p \neq -1 \to \frac{x^{p+1}}{p+1}|_1^R = \frac{R^{p+1}-1}{p+1}$
			$\displaystyle \lim_{R\to\infty}\frac{R^{p+1}-1}{p+1}$
				$p+1 = 0 \to limit = +\infty$
					diverges
				$\displaystyle p+1 < 0 \to R^{p+1} = \frac{1}{R^{-(p+1)}}\to \frac{1}{+\infty} \to 0$
					converges
	Converges if $p < -1$ for $n^p$ or $p > 1$ for $\displaystyle \frac{1}{n^p}$
	Diverges if $p \geq -1$ for $n^p$ or $p \leq 1$ for $\displaystyle \frac{1}{n^p}$

Modifying improper integrals
	If f is a continuous function and $\displaystyle \int_{a}^{\infty}f(x)$ converges/diverges, then $\displaystyle \int_{b}^{\infty}f(x)dx$ also converges/diverges
	The same idea applies to other improper integrals
		if the difference between two improper integrals is a proper integral, they both have the same qualitative behaviour

Comparison test
	Suppose both f and g are integrable on every close subinterval of a give interval $(a, b)$ (Allow both $a = -\infty$ and $b = +\infty$)
		f is complicated (given) $\to$ g is simpler
		1) If $|f(x)| \leq g(x)$ for all x in $(a, b)$ and if $\displaystyle \int_{a}^{b}g(x)dx$ converges, then $\displaystyle \int_{a}^{b}f(x)dx$ also converges
		2) If $|f(x)| \geq g(x) \geq 0$ for all x in $(a, b)$ and if $\displaystyle \int_{a}^{b}g(x)dx$ diverges, then $\displaystyle \int_{a}^{b}f(x)dx$ also diverges
	Simpler functions can be $x^p$ or $e^x$
	You should focus on the highest order

[[MATH 101 Discussion 07]]