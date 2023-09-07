$\displaystyle \frac{1}{1+x^2}=\frac{1}{1-(-x^2)}\to y = -x^2\to\frac{1}{1-y} = \sum_{n=0}^{\infty}y^n$
	$\displaystyle =\sum_{n=0}^{\infty}(-x^2)^n=\sum_{n=0}^{\infty}(-1)^nx^{2n}$

McLaurin series:
	$\displaystyle \sum_{n=0}^{\infty}\frac{f^{(n)}(c)}{n!}(x-c)^n \to \sum_{n=0}^{\infty}\frac{f^{(n)}}{n!}(x)$
		$c = 0$

$\displaystyle \arctan(x) = \arctan(0) + \sum_{0}^{\infty}\frac{d}{dx}\arctan(s)ds$
	$\displaystyle \arctan(0) +\int_{0}^{x}\frac{1}{1+s^2}ds$
		$\displaystyle = \int_{0}^{\infty}\sum_{n=0}^{\infty}(-1)^ns^{2n}ds$
		$\displaystyle = \sum_{n=1}^{\infty}\int_{0}^{x}(-1)^ns^{2n}ds$
		$\displaystyle =\sum_{n=0}^{\infty}(-1)^n\frac{x^{2n+1}}{2n+1}$
What happens if $x= \pm 1$?
	$x = 1$
		$\displaystyle \sum_{n=0}^{\infty}(-1)^n\frac{1}{2n+1}$
			converges by alternating series test

For $-1 \leq x \leq 1$
	$\displaystyle \arctan(x) = \sum_{n=0}^{\infty}(-1)^n\frac{x^{2n+1}}{2n+1}$
		Abel's theorem for endpoints

$\displaystyle \tan(\frac{π}{4}) = 1$
$\displaystyle π = 4\arctan(1)$
Compute approximation of π using the first 5 terms of the McLaurin series of $\arctan(x)$

Consider alternating series
	$\displaystyle S = \sum_{n=0}^{\infty}(-1)^nA)n$, partial sums
	$\displaystyle S_N = \sum_{n=0}^{N})(-1)^nA_n$, then S is between $S_N$ and $S_{N+1}$
		$|S-S_N| \leq A_{N+1}$

$\displaystyle \left|π-\sum_{n=1}^{N}(-1)^n\frac{1}{2n+1}\right| \leq \frac{1}{2(N+1)+1} = \frac{1}{2N+3}$

$\displaystyle \tan(\frac{π}{6}) = \frac{1}{\sqrt{3}}$:
	$\displaystyle π = 6\arctan(\frac{1}{\sqrt{3}})$
	$\displaystyle =6\sum_{n=0}^{\infty}(-1)^n\frac{(\frac{1}{\sqrt{3}})^{2n+1}}{2n+1}$
	$\displaystyle \left| π - \sum_{n=0}^{N} (-1)^n\frac{(\frac{1}{\sqrt{3}})^{2n+1}}{2n+1}\right| \leq \frac{(\frac{1}{\sqrt{3}})^{2(N+1)+1}}{2(N+1)+1}$
	$\displaystyle \frac{1}{\sqrt{3}}\sum_{n=0}^{N} (-1)^n \frac{(\frac{1}{3^n})}{2n+1}$

[[MATH 101 Lecture 11]]