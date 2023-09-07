If $\displaystyle a_n = (-1)^nb_n$ or $(-1)^{n+1}b_n$ for some $b_n>0$ (this means the series is alternation), and $a_n \to 0$ (or equivalently $b_n \to 0$), then 
	$\displaystyle \sum_{n=1}^{\infty}a_n$ converges

Absolute and conditional convergence
1) A series $\displaystyle \sum_{n=1}^{\infty} a_n$ is called absolutely convergent when the series $\displaystyle \sum_{n=1}^{\infty}|a_n|$ converges
2) A series $\displaystyle \sum_{n=1}^{\infty}a_n$ is called conditionally convergent when it converges, bit the series $\displaystyle \sum_{n=1}^{\infty}|a_n|$ diverges

Comparison Tests
Let $N_0$ be an integer and let $K>0$ 
1) If $|a_n| \leq Kc_n$ for all $n\geq N_0$, and $\displaystyle \sum_{n=1}^{\infty}c_n$ converges, then $\displaystyle \sum_{n=1}^{\infty}a_n$ converges absolutely
	$\displaystyle c_n \geq 0 \to |a_n| \leq c_n \to \sum_{n=1}^{\infty}|a_n| \leq \sum_{n=1}^{\infty}c_n$ 
		smaller than convergent and positive $\to$ convergent 
2) if $a_n \geq Kd_n \geq 0$ for all $n \geq N_0$, and $\displaystyle \sum_{n=1}^{\infty}d_n$ diverges, then $\displaystyle \sum_{n=1}^{\infty}a_n$ diverges
	$\displaystyle d_n \geq 0 \to a_n \geq d_n \to \sum_{n=1}^{\infty}a_n \geq \sum_{n=1}^{\infty}d_n \to +\infty \to \sum_{n=1}^{\infty}a_n = +\infty$ 

Ex) Does $\displaystyle \sum_{n=1}^{\infty}\frac{1}{n^2+2n+3}$ converge or diverge?
	Compare to largest power: compare to $\displaystyle \frac{1}{n^2}$
		$\displaystyle \frac{1}{n^2+2n+3} \leq \frac{1}{n^2}$
		By the comparison test, it converges (absolutely)

Limit comparison test:
	Take $\displaystyle \sum_{n=1}^{\infty}a_n$ and $\displaystyle \sum_{n=1}^{\infty}b_n$ with $a_n \geq 0$ and $b_n \geq 0$. Let $\displaystyle L = \lim_{n\to \infty}\frac{a_n}{b_n}$
		$b_n$ ~$La_n$ for large n
	1) If $0 < L < \infty$, then $\displaystyle \sum_{n=1}^{\infty}a_n$ have the same convergence/divergence property as $\displaystyle \sum_{n=1}^{\infty}b_n$
	2) If $L=0$ and $\displaystyle \sum_{n=1}^{\infty}b_n$ converges, then $\displaystyle \sum_{n=1}^{\infty}a_n$ converges
		$a_n << b_n$
	3) If $L = \infty$ and $\displaystyle \sum_{n=1}^{\infty}b_n$ diverges, then $\displaystyle \sum_{n=1}^{\infty}a_n$ diverges
		$a_n >> b_n$
	1) If anything else, test is inconclusive
		$L$ does not exist = oscillates

Ex) Does $\displaystyle \sum_{n=2}^{\infty}\frac{\sqrt[3]{n}}{n^2-n}$
$b_n \to$ dominating terms $\displaystyle \to \frac{\sqrt[3]{n}}{n^2}=n^{-5/3}=\frac{1}{n^{5/3}}$
	P-test, $\displaystyle p = \frac{5}{3} > 1 \to \sum_{n=1}^{\infty}b_n$ converges

$\displaystyle \lim_{n\to\infty}\frac{\sqrt[3]{n}}{n^2-n}/\frac{[3]{n}}{n^2} = \lim_{n\to\infty}\frac{n^2}{n^2-n} \to 1 = L$
	By limit comparison test, $\displaystyle \sum_{n=1}^{\infty}a_n$ converges

Ex) Does $\displaystyle \sum_{n=1}^{\infty}\frac{2^n+log(n)}{e^n+sin(n)}$ converge or diverge?
	Similar to $\displaystyle \frac{e^n}{e^n}$ but more complicated
	Focus on dominating terms
	$\displaystyle b_n = \frac{2^n}{e^n} = (\frac{2}{e})^n$
		geometric series
		$\displaystyle 0<\frac{2}{e}<1 \to$ converges
	$\displaystyle \lim_{n\to\infty}\frac{2^n+log(n)}{2^n}\cdot\frac{e^n}{e^n+sin(n)}$
	$\displaystyle = \lim_{n\to\infty}(1+\frac{log(n)}{2^n})\frac{1}{\frac{e^n+sin(n)}{e^n}}$
	$\displaystyle  = \lim_{n\to\infty}(1+\frac{log(n)}{(2^n})\frac{1}{1+\frac{sin(n)}{e^n}} \to \frac{bounded}{\infty}$
	$\displaystyle L = 1$, converges

Ex) Does $\displaystyle \sum_{n=1}^{\infty}\frac{1}{n\sqrt{3\log(n)+2}}$ converge or diverge?
	$\displaystyle b_n = \frac{1}{n\sqrt{3\log(n)}} = \frac{1}{n\sqrt{3}\sqrt{\log(n)}}=\frac{1}{\sqrt{3}}\frac{1}{n(\log(n))^{1/2}}$
	Last time: $\displaystyle \sum_{n=1}^{\infty}\frac{1}{n(\log(n))^p}$
		converges if $p > 1$: integral test
		diverges if $p\leq 1$ ($p \leq 1$)
	$\displaystyle \lim_{n\to\infty}\frac{a_n}{b_n}=\lim_{n\to\infty}\frac{n\sqrt{3\log(n)}}{n\sqrt{3\log(n)+2}} \to 1 = L$

Ratio test
	Given a series $\displaystyle \sum_{n=1}^{\infty}a_n$, let $\displaystyle L = \lim_{n\to\infty}|\frac{a_{n+1}}{a_n}|$
	1) If $L < 1$, the series $\displaystyle \sum_{n=1}^{\infty}|a_n|$ converges (so does $\displaystyle \sum_{n=1}^{\infty}a_n$ does too)
	2) If $L > 1$ (or $L = +\infty$), the series $\displaystyle \sum_{n=1}^{\infty}a_n$ diverges (so does $\displaystyle \sum_{n=1}^{\infty}|a_n|$ does too)
	3) If $L=1$ or if $L$ does not exist, the test is inconclusive
		The limit if a geometric series
			Geometric series converge when the base, in this case, $L < 1$
Remarks:
	1) If $\displaystyle \sum_{n=1}^{\infty}|a_n|$ converges, the size of L give information about the speed of convergence for the series
		1) If $L=1$, convergence will be very slow if it happens at all (outside info needed)
		2) if $L < 1$ but $L \approx 1$, convergence will be slow but acceptable
		3) If $L\approx 0$, convergence will be fast enough for practical purposes
		4) If $L=0$, convergence will be super fast
	2) The ratio test is useful when the terms in the series involve $n$ as an exponent, and/or in factorials
		Eg) $\displaystyle \sum_{n=1}^{\infty}\frac{n2^n}{5^n}$
	3) The ratio test is useless for series like $\displaystyle \sum_{n=1}^{\infty}\frac{P(n)}{Q(n)}$, where $P(n)$$ and $Q(n)$ are polynomials, because $L = 1$

Eg) Test these series for convergence
1) $\displaystyle a_n = \frac{e^n}{n!}$
	$\displaystyle a_{n+1} = \frac{e^{n+1}}{(n+1)!}$
	$\displaystyle |\frac{a_{n+1}}{a_n}|=\frac{e^{n+1}n!}{e^n(m+1)!}$
	$\displaystyle \lim_{n\to\infty}\frac{e^{n+1}}{e^n}\frac{n!}{(n+1)!} = \frac{e}{n+1} = 0$
3) $\displaystyle a_n = \frac{r^n}{n^p}, a_{n+1}=\frac{r^{n+1}}{(n+1)^p} \to |\frac{a_{n+1}}{a_n}| = \frac{|r|^{n+1}n^p}{|r|^n(n+1)^p}=|r|(\frac{n}{n+1})^p$
	$\displaystyle \lim_{n\to\infty}|\frac{a_{n+1}}{a_n}| = \lim_{n\to\infty}|r|(\frac{n}{n+1})^p = |r| = L$
		If $|r| < 1 \to$ Converges with ratio test
		If $|r| > 1 \to$ Diverges with ratio test
		If $|r| = 1 \to$ Keep working

[[MATH 101 Discussion 09]]