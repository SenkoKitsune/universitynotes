Limit comparison test
Take $f$ and $g$ continuous and $g(x) > 0$
1) If $\displaystyle \int_{a}^{\infty} g(x)dx$ converges and the limit $\displaystyle \lim_{x\to \infty}\frac{f(x)}{g(x)}$ exists, then $\displaystyle \int_{a}^{\infty} f(x)dx$ converges
2) If $\displaystyle \int_{a}^{\infty} g(x)dx$ diverges and the limit $\displaystyle \lim_{x\to \infty}\frac{f(x)}{g(x)}$ exists and is non-zero, then  $\displaystyle \int_{a}^{\infty} f(x) dx$ diverges

A sequence is an infinite list of numbers $\displaystyle (a_n)_{n = 1}^{\infty} = (a_1, a_2, ... )$
We can say the sequence has a limit L if the values approach L as $n \to \infty$
Often, a sequence is given by a function $\displaystyle a_n = f(n)$ 

 series is a sum of infinitely many numbers
	 $\displaystyle S = \sum_{n = 1}^{\infty}a_n = a_1+ a_2 + ...$
There are two different sequences associated to a series
 1) Sequence $\displaystyle (a_n)_{n=1}^{\infty}$
 2) Sequence of partial sums
	$\displaystyle S_N = a_1 + a_2 + ... + a_N =\sum_{n=1}^{N}a_N$
A series converges if the sequence of partial sums $S_N$ has a limit L, which is a number
	$\displaystyle \sum_{n=1}^{\infty}a_n = L$, where L is the sum of the series:
	$\displaystyle S = \lim_{n \to \infty}S_N = \lim_{n \to \infty}\sum_{n = 1}^{N}a_n = \sum_{n=1}^{\infty}a_n$

If the sequence of partial sums does not converge to a number, we say the series diverges

Telescoping series
$\displaystyle \sum_{n=1}^{\infty}\frac{1}{n(n+1)}$

1) Use the partial fractions method to find $A,B$ such that $\displaystyle \frac{1}{n(n+1)} = \frac{A}{n} + \frac{B}{n+1}$
2) Find $\displaystyle \sum_{n=1}^{6}\frac{1}{n(n+1)}$
3) For any $N$, find the partial sum $\displaystyle S_N = \sum_{n=1}^{N}\frac{1}{n(n+1)}$
4) Show that the series $\displaystyle \sum_{n=1}^{\infty}\frac{1}{n(n+1)}$

1) $\displaystyle \frac{1}{n(n+1)} = \frac{A}{n} + \frac{B}{n+1}$
	A = 1, B = -1
2) $\displaystyle S_5 = \frac{1}{1} - \frac{1}{2} + \frac{1}{2} -\frac{1}{3} + \frac{1}{3} - \frac{1}{4} + \frac{1}{4} - \frac{1}{5} + \frac{1}{5} - \frac{1}{6} = \frac{5}{6}$
3) $\displaystyle S_N = \frac{1}{1} - \frac{1}{2}+\frac{1}{2}-\frac{1}{3}+\frac{1}{3} - ... + \frac{1}{N-1} - \frac{1}{N} + \frac{1}{N} - \frac{1}{N+1}$
	$\displaystyle \lim_{N \to \infty}S_N = 1$

A telescoping series $\displaystyle \sum_{n=1}^{\infty}a_n$ is one in which the terms $a_n$ have the special form $a_n = b_n - b_{n-1}$ for some sequence $b_n$
Consider the telescoping series
	$\displaystyle S = \sum_{n=1}^{N}(b_n - b_{n+1})$
	If $\displaystyle \lim_{n\to \infty}b_n$ does not exist or is $\infty$, then S diverges
	If $\displaystyle \lim_{n\to \infty}b_n = B$, then S converges to $b_1 - B$
$\displaystyle S = \sum_{n=1}^{N}(b_n - b_{n+1}) = (b_1-b_2)+ (b_2-b_3)+(b_3-b_4) + ... + (b_{N-1}-b_N) + (n_N - b_{N+1}) = b_1 - b_{N+1}$
$\displaystyle S = \lim_{N \to \infty}S_N = b_1 - B$ if the limit exists, and does not converge otherwise

Eg.) $\displaystyle \sum_{n=3}^{\infty}log(1+\frac{1}{n})$
$\displaystyle log(1+\frac{1}{n}) = log{\frac{n}{n}+\frac{1}{n}} = log(n+1) - log(n) = -log(n) - (-log(m+1))$
$\displaystyle S_n = -log(3)+log(4) - log(4) + log(5) - log(5) + log(6) - ... - log(N) + log(N+1)$
	$\displaystyle S_N = -log(3) + log(N+1)$
	$\displaystyle S = \lim_{n\to\infty}S_N = \lim_{N\to\infty} - log(3) + log(N+1) = +\infty$
		The series diverges

The divergence test
Eg.) Show that the following two series diverge
1) $\displaystyle \sum_{n=1}^{\infty}(-1)^n = -1 + 1 - 1 + 1 - ...$
2) $\displaystyle \sum_{n=1}^{\infty} \frac{n}{n+1}$

$\displaystyle a_n = \pm 1 \to a_n \nrightarrow 0$
$\displaystyle a_n = \frac{n}{n+1} \to 1$ as $n \to \infty$


1) $\displaystyle S_1 = -1, S_2 = 0, S_3 = -1 \to S_N = (-1, 0 ,-1, 0,-1, 0, ... )$
	Does not have a limit $\to$ S diverges
2) $\displaystyle \frac{n}{n+1} \geq \frac{1}{2} \to (\frac{1}{2},\frac{2}{3},\frac{3}{4},\frac{4}{5}, ... )$
	$\displaystyle a_1 + a_2 + ... + a_N \geq \frac{1}{2} + \frac{1}{2} + ... \frac{1}{2} = \frac{1}{2}\cdot N \to \infty$

If the terms $a_n$ of a series do not approach 0, the series has no hope of converging

If the sequence $\displaystyle (a_n)_{n = 1}^{\infty}$ does not converges to zero as $n \to \infty$ (this means that either $a_n$ des not have a limit, or it has a limit different than 0), then $\displaystyle \int_{n=1}^{\infty}a_n$ diverges

The divergence test gives no information when $a_n \to 0$ as $n\to \infty$


Integral test
We will se the series $\displaystyle \int_{n=1}^{\infty} \frac{1}{n^2}$ converges by comparing it to an integral
	Visualise $\displaystyle f(x) = \frac{1}{x^2}$
	Each rectangle has width 1 $\displaystyle \to \frac{1}{4}, \frac{1}{9}, \frac{1}{16}$ because we are using integer points for lengths
		$\displaystyle \sum_{n=1}^{\infty}\frac{1}{n^2} = 1 + \sum_{n=2}^{\infty}\frac{1}{n^2}= 1 +$ area of all rectangles
	The curve is $\displaystyle y = \frac{1}{x^2}$ and the rectangles touch at the top right corner
		All of the rectangles should be under the curve, which is the integral of the function
		Area of all rectangles $\displaystyle <  \int_{1}^{\infty}\frac{1}{x^2}dx < +\infty \to$ area under curve
	Then
		$\displaystyle \int_{1}^{\infty}x^{-2}dx < + \infty$ by P-test $(-2 < -1)$
	The series converges
This method provides an inequality involving the infinite series
$\displaystyle \sum_{n=1}^{\infty}\frac{1}{n^2} = \frac{π^2}{6}$

We will now use a similar idea to show that $\displaystyle \sum_{n=1}^{\infty}\frac{1}{n}$ diverges by comparing it to an integral
	Important series called the harmonic series

We will be using the graph of the function $\displaystyle f(x) = \frac{1}{x}$
	The rectangle will be larger than the area under the curve because we are trying to prove divergence
	The rectangles have width one and height $\displaystyle 1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, ...$
		$\displaystyle \sum_{n=1}^{\infty}\frac{1}{n}$ = area of all the rectangles
		The curve is $y = \frac{1}{x}$ and the rectangles touch the curve at the top left corner
			Area of rectangles $\displaystyle > \int_{1}^{\infty}\frac{1}{x}dx$
				$\displaystyle \int_{1}^{\infty}x^{-1}dx \to P = -1 \to$ diverges by P-test $\to +\infty$
		Then
		$\displaystyle \sum_{n=1}^{\infty}\frac{1}{n} = +\infty$

Integral test
		Let $N_0$ be a positive integer and let $f(x)$ be a continuous function for all $x \geq N_0$. We are interested in the series $\displaystyle \sum_{n=1}^{\infty}f(n)$
		Assume that:
		1) $f(x) \geq 0$ for all $x \geq N_0$
		2) $f(x)$ is a decreasing function for all $x \geq N_0$ ( if $f$ is differentiable, this can be checked by $f'(x) < 0$ 
		Then
		A) if $\displaystyle \int_{N_0}^{\infty}f(x)dx$ converges, then $\displaystyle \sum_{n=1}^{\infty}a_n$ converges
		B) if $\displaystyle \int_{N_0}^{\infty}f(x)dx$ diverges, then $\displaystyle \sum_{n=1}^{\infty}a_n$ diverges
	The number $N_0$ in the theorem helps by allowing the hypotheses to hold for sufficiently large values of x
	If one or both condition fail, the test is inconclusive
	Does not tell the value of convergence, but we can obtain error bound

For what values $p > 0$ does $\displaystyle \sum_{n=1}^{\infty}\frac{1}{n^p}$ converge
	$\displaystyle f(x) = \frac{1}{x^p} > 0$, decreasing
	$(i)$ and $(ii)$ are satisfied
	$\displaystyle \int_{1}^{\infty}\frac{1}{n^p}dx = \int_{1}^{\infty}x^{-p}dx$
		converges if $-P < -1 \leftrightarrow P>1$
		diverges if $-P \geq -1 \leftrightarrow P \leq 1$

For what values of $p \geq 0$ does $\displaystyle \sum_{n=2}^{\infty}\frac{1}{n(log(n))^p}$?
$\displaystyle f(x) = \frac{1}{x(log(x))^p}$ if $x > 1$
	decreasing if $x > 1$ because x increases, $(log(x))^p$ increases, but in denominator
	$\displaystyle \int_{2}^{\infty}\frac{1}{x(log(x))^p}dx \to u = log(x) du = \frac{1}{x}dx$
	$\displaystyle \to \int u^{-p}du = \frac{u^{-p+1}}{-p+1}$ if $\displaystyle p \neq 1 \to \frac{(log(x))^1-p}{1-p}+C$
		=$\displaystyle ln|u|$ if $p = 1 \to log|log(x)| + C$
		$\displaystyle \int_{2}^{\infty} = \lim_{R \to \infty}\int_{2}^{R}\frac{1}{x(log(x)^p)}dx \to p \neq 1 \to \lim_{R \to \infty}\frac{(log(R))^{1-p}}{1-p} -\frac{(log(2))^{1-p}}{1-p}$
			$+\infty$ if $1 - p > 0$
			$\displaystyle -\frac{(log(2))^{1-p}}{1-p}$ if $1-p < 0$

Integral test for error control
	If a series $\displaystyle S = \sum_{n=1}^{\infty}a_n$, then the partial sums $\displaystyle S_N = \sum_{n=1}^{N}a_n$ converge to S
	It is useful to know how close $S_N$ is to $S$ for a given value of $N$
	Truncation error
		$\displaystyle R_N = |S-S_N| = |\sum_{n=1}^{\infty}f(n) - \sum_{n=1}^{N}a_n| = |a_{N+1} + a_{N+2}+ ... |$
	Let $f(x)$ be a non-negative decreasing function for all $x \geq N_0$ Then for $N \geq N_0$
		$\displaystyle R_N = |S - S_N| = |\sum_{n=1}^{\infty}f(n) - \sum_{n=1}^{N}f(n)| < \int_{N}^{\infty}f(x)dx$

Eg.) Using that $\displaystyle \sum_{n=1}^{100}\frac{1}{n^2} = 1.634884$, find a short interval containing the number $\displaystyle S = \sum_{n=1}^{\infty}\frac{1}{n^2}$
	$\displaystyle \frac{1}{x^2} > 0$ and decreasing
	Error term: $\displaystyle |S - S_100| < \int_{100}^{\infty}f(x)dx$
		$\displaystyle \int x^{-2}dx = -x^{-1}+C \to \lim_{R \to \infty}\int_{100}^{R}\frac{1}{x^2}dx = \lim_{R \to \infty}-\frac{1}{x}\vert_{100}^{R} = \lim_{R\to \infty}-\frac{1}{R}+\frac{1}{100} = \frac{1}{100}$
		$\displaystyle S \in [1.634884 - \frac{1}{100}, 1.634884 + \frac{1}{100}]$

[[MATH 101 Discussion 08]]