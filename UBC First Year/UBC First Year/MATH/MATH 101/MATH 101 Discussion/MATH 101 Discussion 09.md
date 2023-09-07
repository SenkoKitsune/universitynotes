Power series and radius of convergence
Geometric series $\displaystyle \sum_{n=0}^{\infty}r^n$
	$|r| < 1$ converges
		$\displaystyle \sum_{n=0}^{\infty}r^n=\frac{1}{1-r}$
	$|r| \geq 1$ diverges

Series represents the function
	$f: (-1,1)\to \mathbb{R}$
	$\displaystyle f(r)=\frac{1}{1-r}=\sum_{n=0}^{\infty}r^n$

A power series is a series of the form
	$\displaystyle \sum_{n=0}^{\infty}A_n(x-c)^n$
		$c$ is the centre
		$A_n$ are called coefficients

Eg) For what values of $x$ does $\displaystyle \sum_{n=1}^{\infty}\frac{1}{n}x^n$ converge?
	$c=0$
	Using ratio test
	$\displaystyle \frac{n}{n+1}|x|\to_{n\to\infty}|x|$
	Testing:
		$\displaystyle x=1: \sum_{n=1}^{\infty}\frac{1}{n}$ diverges
		$\displaystyle x=-1 \sum_{n=1}^{\infty}\frac{(-1)^n}{n}$ converges
		$x=0$ converges

Consider $\displaystyle \sum_{n=1}^{\infty}A_n(x-c)^n$
	Assume $\displaystyle \lim_{n\to\infty}|\frac{A_{n+1}}{A_n}| = A$
		For which $x$ does $\displaystyle \sum_{n=1}^{\infty}A_n(x-c)^n$ converge?
			$\displaystyle a_n = A_n(x-c)^n$
			$x=c$ converges $A_n(c-c)^n=0$
			$x\neq c$:
				$\displaystyle |\frac{a_{n+1}}{a_n}=|\frac{A_{n+1}(x-c)^{n+1}}{A_n(x-c)^n}|$
				$\displaystyle |\frac{A_{n+1}}{A_n}|\cdot |x-c| \longrightarrow_{n\to\infty} A\cdot |x-c|$
					$A|x-c| < 1 \to$ converges
					$A|x-c| > 1 \to$ diverges
					$A|x-c| = 1 \to$ inconclusive
						$\displaystyle |x-c|<\frac{1}{A} \to (c-\frac{-1}{A},c+\frac{1}{A})$
						$A|x-c| = 0$ converges for all x

Def: If $\displaystyle A = \lim_{n\to\infty}|\frac{A_{n+1}}{A_n}|$ exists, then we call $\displaystyle R = \frac{1}{A}$ the radius of convergence

When $A=0 (R=\infty)$
	$\displaystyle \sum_{n=1}^{\infty}A_n(x-c)^n$ has infinite radius of convergence
When $A = \infty(R=0)$
	$\displaystyle \sum_{n=1}^{\infty}A_n(x-c)^n$ has radius of convergence equal to 0

$\displaystyle \sum_{n=1}^{\infty}A_nx^n$ where $A_n = \begin{equation*}\left\{ \begin{aligned}2, n_{odd}\\1, n_{even} \end{aligned}\right.\end{equation*}$
	$a_n = A_nx^n$
	$x\neq 0$
	$\displaystyle |\frac{a_{n+1}}{a_n}=|\frac{A_{n+1}}{A_n}\cdot|x|$
		oscillates, cannot use ratio test
	Comparison test:
	$\displaystyle |A_nx^2| = |A_n||x|^n \leq 2\cdot|x|^n$
		$\displaystyle \sum_{n=1}^{\infty}2|x|^n$ converges for $|x|<1$
			$|x| \geq 1$ diverges

[[MATH 101 Lecture 10]]