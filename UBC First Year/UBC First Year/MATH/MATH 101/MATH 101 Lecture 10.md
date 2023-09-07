A power series is a series of the form
	$\displaystyle \sum_{n=0}^{\infty} A_n(x-c)^n$
		If $x=c\to(x-c)^n = 0 + 0 + 0 + ... = 0$
	Here $A_n$ are given coefficients and c is a given number, while $x$ is a variable
	We say the series is cantered at $c$. Very often, we can take $c=0$ so we get $\displaystyle \sum_{n=0}^{\infty} A_nx^n$
	
Radius of convergence: for each power series, one of the following always occurs
1) The power series converges for all $x\in R$. In this case, $R = \infty$
2) There is some number $R\in (0, \infty)$ such that the series converges when $|x-c| < R \to (C-R) < x < (C+R)$ and diverges when $|x-c| > R$ The radius of convergence is R
3) The series diverges for all $x\neq c$ (it always converges when $x=c$) The radius of convergence is $R = 0$
When the radius of convergence is $R\in(0, +\infty)$
	The convergence is always absolute for $x\in (c-R, c+R)$
	At $x=c-R$ and $x-c+R$, the series may converge (absolutely or conditionally) or diverge

The interval of convergence is the set of all values of $x$ for which the series converges
	If $R = +\infty$, then it is $(-\infty, +\infty)$
	If $R\in (0, +\infty)$ and is one of: $[c-R,c+R], [c-R,c+R),(c-R,c+R],$ or $(c-R,c+R)$ and all of these are possible
To determine the radius of convergence, we use the ratio test. When the radius of convergence is $R\in (0,+\infty)$, to determine the convergence at $x=c-R$ and $x=c+R$, we have to use other tests, on a case by case basis
When the radius of convergence is $> 0$ (a positive number or $+\infty$), the power series defines a function
	$\displaystyle \sum_{n=0}^{\infty} A_n(x-c)^n$
	whose domain is the interval of convergence. Power series generalize polynomials (which correspond tot he case where all but finitely many of the $A_n$ are 0)

Find the radius and convergence of $\displaystyle \sum_{n=1}^{\infty} (-1)^n\frac{2^n}{n}(x-1)^n$
Ratio test: ($(-1)^n$ cancels due to absolute value
	$\displaystyle |a_n| = \frac{2^n}{n}|x-1|^n$
	$\displaystyle |a_{n+1}|=\frac{2^{n+1}}{n+1}|x-1|^{n+1}$
		$\displaystyle \frac{a_{n+1}}{|a_n|}=\frac{2^{n+1}||x-1|^{n+1}\cdot n}{2^n|x-1|^n\cdot(n+1)}\to \frac{2|x-1|\cdot n}{n+1}$
		$\displaystyle \lim_{n\to\infty}|x-1|(2)\frac{n}{n+1} = 2|x-1|(1)$
	$2|x-1|$
		$<1$: converges: $2|x-1||c|\to|x-1| < \frac{1}{2}\to$ Radius of convergence is $\displaystyle \frac{1}{2}$
		$=1$: inconclusive
		$>1$: diverges
$\displaystyle x=\frac{1}{2} \to \sum_{n=1}^{\infty} (-1)^n\frac{2^n}{n}(\frac{1}{2}-1)^n = \sum_{n=1}^{\infty} \frac{1}{n^1}\to$ diverges by the P-test
	$\displaystyle \frac{2^n}{n}\frac{(-1)^n(-\frac{1}{2})^n}{(-1\cdot -\frac{1}{2})^n}=\frac{1}{2}^n$
$\displaystyle x=\frac{3}{2} \to (-1)^n\frac{2^n}{n}(\frac{3}{2}-1)^n = \frac{(-1)^n}{n}2^n(\frac{1}{2})^n = \frac{(-1)^n}{n}2^n \to \sum_{n=1}^{\infty} (-1)^n\frac{1}{n}$
	1) Alternating
	2) $\displaystyle \frac{1}{n}$ is decreasing
	3) $\displaystyle \frac{1}{n} \to 0$ as $n\to +\infty$
		Converges by the alternating series test
Interval of convergence $\displaystyle \left(\frac{1}{2},\frac{3}{2}\right]$

Geometric series is one of the form
$\displaystyle \sum_{n=0}^{\infty} Ar^n = \sum_{n=1}^{\infty} Ar^{n-1} = A + A_r + Ar^2 + Ar^3 + ...$
The geometric series converges if $|r| < 1$ and diverges if $|r| \geq 1$ 
	$\displaystyle \sum_{n=1}^{\infty} Ar^{r-1} = \frac{A}{1-r}$

If we take $A=1$ and write $x$ in place of $r$, we get the geometric power series
	$\displaystyle \sum_{n=0}^{\infty} x^n = \sum_{n=1}^{\infty} x^{n-1} = 1 + x + x^2 + x^3 + ...$

The centre of the geometric series is $c-0$ and the coefficients $A_0, A_1, ...$ are all 1

The geometric series converges when $|x| < 1$ and diverges when $|x| \geq 1$, so the radius of convergence is $R=1$, and the interval of convergence is $(-1,1)$

Eg) Representing a function $\displaystyle \frac{1}{1-x}$ by means of a power series
The domain of $\displaystyle \frac{1}{1-x}$ is all reals except $1$. The power series only converges for $x\in (-1,1)$ If $x=2$, then $\displaystyle \sum_{n=1}^{\infty}\frac{1}{1-x} = -1$ but $\displaystyle \sum_{n=0}^{\infty} x^n$ diverges

We can replace "$x$" by any other expression (so long as the absolute value is < 1)
	If $|x^2 - 1| < 1$, then
	$\displaystyle \frac{1}{2-x^2}=\frac{1}{1-(x^2-1)} = 1 + (x^2-1)+(x^2-1)^2 + ...$


Manipulating power series
Eg) Find the power series representation for 
	$\displaystyle \frac{1}{1-y} = \sum_{n=0}^{\infty} y^n = 1 + y + y^2 + ...$ if $|y| < 1$
$\displaystyle f(x) = \frac{2}{1-x}$
	$\displaystyle \frac{2}{1-x} = 2\frac{1}{1-x} = 2(1+x+x^2+...)= 2 + 2x + 2x^2 + ... = \sum_{n=0}^{\infty} 2x^n \to R = 1$
$\displaystyle g(x) = \frac{2x^2}{1-x}$
	$\displaystyle \frac{2x^2}{1-x}=2x^2(\frac{1}{1-x}) = 2x^2(1+x+x^2+...)=2x^2+2x^3+2x^4+2x^5+... = \sum_{n=2}^{\infty} 2x^n = \sum_{n=0}^{\infty} 2x^{n+2}\to R = 1$
$\displaystyle h(x) = \frac{1}{1-2x}$
	$\displaystyle \frac{1}{1-2x} = 1 + 2x + (2x)^2 + (2x)^3 + ... = 1 + 2x + 2^2x^2 + 2^3x^3 + ... = \sum_{n=0}^{\infty} 2^nx^n \to R = \frac{1}{2}$
	$\displaystyle y \to 2x \to |y| < 1 \to |2x|<1 \to 2{x} < 1 \to |x| < \frac{1}{2} \to R$
$\displaystyle p(x) = \frac{1}{1+x}$
	$\displaystyle \frac{1}{1+x}\to y=-x \to \frac{1}{1-y}=\frac{1}{1+x}$
	$\displaystyle \frac{1}{1+x} = \frac{1}{1-(-x)} = 1-x+x^2-x^3+x^4-x^5 = 1 + (-1)x+(-1)^2x^2+(-1)^3(x^3)+... = \sum_{n=0}^{\infty} (-1)^nx^n$
	Converges if $|y| < 1 \leftrightarrow |-x| < 1 \to |x| < 1 \to R = 1$

  Let $\displaystyle S(x) = \sum_{n=0}^{\infty} A_n(x-c)^n$, for $x$ in the interval of convergence
The derivative/indefinite integral of a finite sum is the sum of the derivatives/indefinite integrals. The good news is that for power series, within the interval of convergence (not necessarily at the endpoints) this is very useful property extends to infinite sums

If the power series:
	$\displaystyle S(x) = \sum_{n=0}^{\infty} A_n(x-c)^n$
Has radius of convergence $R > 0$ (possibly infinite) then on the interval $|x-c| < R$ (or for all $x$ when $R = \infty$)
	$\displaystyle x \in (C-R, C+R)$
		For x = $c-R, c+R$, formula doesn't work
	$\displaystyle S'(x) = \frac{dS}{dx} = \sum_{n=1}^{\infty} nA_n(x-c)^{n-1}$
	$\displaystyle \int S(x)dx = \sum_{n=1}^{\infty} A_n \frac{(x-c)^{n+1}}{n+1}+C$

The previous theorem means that we are allowed to differentiate and integrate $S(x)$ term-by-term in $|x-c| < R$ 
The indexing of the power series $S'(x)$ starts at $n=1$ because the first term $A_0' = 0$
We can get higher order derivatives by differentiating again:
	$\displaystyle S''(x) = \frac{d^2S}{ds^2} = \sum_{n=2}^{\infty} n(n-1)A_N(x-c)^{n-2}$

Eg) Show that $\displaystyle \log(1+x) = \sum_{n=0}^{\infty} (-1)^n\frac{x^{n+1}}{n+1}$ for $|x| < 1$
	$\displaystyle \log|1+x| +C = \int \frac{1}{1+x} \to \sum_{n=0}^{\infty} (-1)^nx^n$
	$\displaystyle \int \frac{1}{1+x}dx = \int \sum_{n=0}^{\infty} (-1)^nx^ndx = \sum_{n=0}^{\infty} \int(-1)^nx^ndx = \sum_{n=0}^{\infty} (-1)^n\frac{x^{n+1}}{n+1}+C' = \log(1+x) +C \to log(1+x)+C'', C'' = C-C'$
	To find $C''$, plug $x=0$
		LHS: $0+0+0+...=0$
		RHS: $\log(1+0)+C'' = 0+C'' = 0$
			$C'' = 0$

Taylor polynomials and error
Recall Taylor polynomials
	$\displaystyle T_n(x) = \sum_{n=0}^{\infty} \frac{f^{(k)}(a)}{k!}(x-a)^k=f(a)+f'(a)(x-a)+\frac{f''(a)}{3!}(x-a)^3 + ... + \frac{f^{(n)}(a)}{n!}(x-a)^n$
Let $f(x)$ be $(n+1)$ times differentiable and let $T_n(x)$ be the Taylor polynomial of $f$$ around a point $a$. Let
	$\displaystyle E_n(x) = f(x) - T_n(x)$
Be the approximation error
	$\displaystyle |E_n(x)| \leq \frac{M}{(n+1)!}(x-a)^{n+1}$
	where M satisfies $|f^{(n+1)(c)}|\leq M$ for all $c$ between $x$ and $a$
		M = maximum of $|f^{(n+1)}|$ on $[a,x]$

Using the value of $e$ using the degree 4 Taylor polynomial at 0. What is a bound on the error in this approximation?
	$f(x) = e^x \to f(1) = e$
	$f(0) = e^0 = 1, f'(x) = e^x \to f'(0)=1, f''(x)=e^x\to f''(0)=1, f'''(x) = e^x \to f'''(0) = 1, f^{(4)}(x)=e^x\to f^{(4)}(0)=1$
	$\displaystyle T_4(x)=1+x+\frac{1}{2!}x^2+\frac{1}{3!}x^3+\frac{1}{4!}x^4$
	$\displaystyle e=f(1) \approx T_4(1) = 1+1+\frac{1}{2}+\frac{1}{3!}+\frac{1}{4!}$
	$\displaystyle |e-T_4(1)| = |f(1)-T_4(1)|\leq \frac{M}{5!}1^5=\frac{M}{5!}\to |f^{(5)}(c)|\leq M$ on $[0,1]$
		$e^c \leq M$
		$e^c \leq e^1 = M$

Taylor series
The Taylor series of the function $f(x)$ expanded around $x=c$ is the power series:
	$\displaystyle T(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(c)}{n!}(x-c)^n = f(c) + f'(c)(x-c)+ \frac{f''(c)}{2!}(x-c)^2+\frac{f^{(3)}}{3!}(x-c)^3+...$
	provided the series converges
	Notice that for a Taylor series, each partial sum
	$\displaystyle T_N(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(c)}{n!}(x-c)^n = f(c) = f'(c)(x-c) + ... + \frac{f^{(N)}(c)}{N!})x-c)^N$
	is in fact a Taylor polynomial of degree N for $f(x), expanded about $x=c$
		$\displaystyle T(x) = \lim_{N\to\infty}T_N(x)$ whenever $T(x)$ converges
	In order to build up the Taylor series, the function $f$ must be infinitely differentiable at $c$
	Note that the Taylor series only depends on the derivative of$f$ at the centre point $c$. SO if two functions $f(x)$ and $g(x)$ take the same values on some small interval containing $c$, they will have the same Taylor series
		If there is a power representation for $f(x)$ near $c$, then it must be the Taylor Series
	It may happen that $T(x)$ is actually not equal to f(x), even withing the radius of convergence of $T(x)$
	$\displaystyle f(x)=\lim_{N\to\infty}T_N(x)+E_N(x)$

We have already computed some Taylor series
	$\displaystyle \frac{1}{1-x}=\sum_{n=0}^{\infty} x^n, (|x| < 1)$
	$\displaystyle \log(1+x) = \sum_{n=0}^{\infty} (-1)^n\frac{x^{n+1}}{x+1}, (|x| < 1)$

Find the Taylor series of $e^x$ centred at $x=0$. What is the radius of convergence?
	$\displaystyle f(x) = e^x \to f^{(n)}(x) = e^x \to f^{(n)}(0) = e^0 = 1$
	$\displaystyle f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(0)}{n!}x^n = \sum_{n=0}^{\infty} \frac{1}{n!}x^n$
	Ratio test:
		$\displaystyle |a_n|=\frac{1}{n!}|x|^n$
		$\displaystyle |a_{n+1}| = \frac{1}{(n+1)!}|x|^{n+1}$
		$\displaystyle \frac{|a_{n+1}|}{|a_n|} = \frac{|x|^{n+1}}{|x|^{n}} = \frac{1\times 2\times ... \times n}{1\times 2 \times .. \times (n)\times (n+1)} \to 0$ as $n\to \infty$
			$\displaystyle \frac{|x|}{n+1}$ converges for all x

[[MATH 101 Discussion 10]]