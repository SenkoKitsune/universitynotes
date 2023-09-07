Find the Taylor series of $\sin(x)$ expanded about $x=0$ and its radius of convergence
	$\displaystyle T(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(0)}{n!}(x-0)^n$
	$\displaystyle f(x) = \sin(x) \to f'(x) = \cos(x) \to f''(x) =-\sin(x) \to f'''(x) -\cos(x)$
	$\displaystyle f^{(0)}(0) = 0\to f'(0) = 1 \to f''(0) = =0 \to f'''(0) = -1 \to f^4(0) = 0$
	We note that if:
		$n$ is even $\to f^{(n)}(0) = 0$
		$n$ is odd $\to f^{(n)}(0)$ alternates between 1 and -1
	$\displaystyle T(x) = x - \frac{1}{3!}x^3+\frac{1}{5!}x^5-\frac{1}{7!}x^7+\frac{1}{9!}x^9-\frac{1}{11!}x^{11}+...$
		$\displaystyle =\sum_{n=0}^{\infty} (-1)^n\frac{1}{(2n+1)!}x^{2n+1}$
			From the Taylor series of $\sin(x)$, you don't see it is periodic
	Radius of convergence: Ratio test
		$\displaystyle |a_n| = \frac{|x|^{(2n+1)}}{(2N+1)!}$
		$\displaystyle |a_{n+1}| \frac{1}{(2(n+1)+1)!}|x|^{2(n+1)+1}=\frac{|x|^{(2n+3)}}{(2n+1)!}$
	$\displaystyle \frac{|a_{n+1}|}{|a_n|}=\frac{|x|^{(2n+3)}\cdot (1\times2\times3\times ... \times (2n+1))}{|x|^{(2n+1)}\cdot (1\times 2\times 3\times ... \times (2n+1)\times (2n+2) \times (2n+3))}$
		$\displaystyle =\frac{|x|^2}{(2n+2)(2n+3)}$
		$\displaystyle \lim_{n\to\infty}\frac{|a_{n+1}|}{|a_n|}=\lim_{n\to\infty} \frac{|x|^2}{(2n+2)(2n+3)} = 0 < 1$
			Always converges: $R = +\infty$

Explain why the Taylor series of $\sin(x)$ equals $\sin(x)$ for all $x \in\mathbb{R}$
	Need to show that $|E_N(x)| \to 0$ as $N \to +\infty$
	By error formula:
		$\displaystyle |E_N(x)| \leq \frac{|x|^{N+1}}{(N+1)!}M \to M =$ max of $\displaystyle |f^{(N+1)}(c)|, c\in [0,x] \cup [x,0]$
			$f^{(N+1)}(c) = \pm\sin(c),\pm\cos(c) \leq 1$
			M = 1
		$\displaystyle \lim_{N\to\infty}\frac{|x|^{N+1}}{(N+1)!}=\lim_{N\to\infty}\frac{|x||x|...|x|}{1\times 2\times ... \times(N+1)}$
			$|x| \leq K$ integer
			$\displaystyle =\lim_{N\to\infty}\frac{|x||x|...|x|}{1\times 2 \times .., \times K}\frac{|x|}{K+1}\frac{|x|}{K+2}...\frac{|x|}{N+1} \leq$ some number (bounded) $\to$ tends to zero

Find the Taylor series of $\cos(x)$ expanded about $x=0$, and its radius of convergence
	$\displaystyle \sin(x) = \sum_{n=0}^{\infty} (-1)^n\frac{x^{2n+1}}{(2n+1)!}$
	$\displaystyle \cos(x) = \frac{d}{dx}\sin(x) = \sum_{n=0}^{\infty} \frac{(-1)^n}{(2n+1)!}(2n+1)x^{2n}$
		$\displaystyle =\sum_{n=0}^{\infty} (-1)^n\frac{x^{2n}}{(2n)!}$
	$R = +\infty$ because radius of convergence does not change when taking derivatives 	

Limits using Taylor series
	$\displaystyle \lim_{x\to 0}\frac{\arctan(x)-x}{\sin(x)-x}$
	$\displaystyle \arctan(x) = x -\frac{x^3}{3}+\frac{x^5}{5}-\frac{x^7}{7}+...$
	$\displaystyle \arctan(x)-x=-\frac{x^3}{3}+\frac{x^5}{5}-\frac{x^7}{7}+...$
	$\displaystyle \sin(x) = x -\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+...$
	$\displaystyle \sin(x) -x = -\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+...$
		$\displaystyle \frac{\arctan(x) -x}{\sin(x)-x} = \frac{-\frac{x^3}{3}+\frac{x^5}{5}-\frac{x^7}{7}+...}{-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+...}$
		$\displaystyle =\frac{-x^3(\frac{1}{3}-\frac{x^2}{5}+\frac{x^4}{7}+...)}{-x^3(\frac{1}{3!}-\frac{x^2}{5!}+\frac{x^4}{7!}+...)}$
		$\displaystyle \lim_{x\to 0} \frac{-x^3(\frac{1}{3}-\frac{x^2}{5}+\frac{x^4}{7}+...)}{-x^3(\frac{1}{3!}-\frac{x^2}{5!}+\frac{x^4}{7!}+...)} = \frac{\frac{1}{3}}{\frac{1}{3!}} = 2$

Use the Taylor series to justify why, no matter how large the value of N,
	$\displaystyle \lim_{x\to\infty}\frac{e^x}{x^N}=+\infty$
(aka. exponential grows more quickly than any polynomial)
	$\displaystyle e^x = 1 + x + \frac{x^2}{2!}+\frac{x^3}{3!} + ...$
	$\displaystyle \frac{e^x}{x^N}=\frac{1}{x^N}+\frac{x}{x^N}+\frac{x^2}{2!x^N}+...+\frac{x^N}{N!x^N}+\frac{x^{N+1}}{(N+1)! x^N}+ ...$
		$\to \infty$

Explain what goes wrong in trying to apply the argument of the previous exercise to show the (false) claim that 
	$\displaystyle \lim_{x\to\infty}\frac{\log(1+x)}{x^N} = +\infty$
	The difference is that Taylor series of $\log(1+x)$ alternates positive and negative and $\infty - \infty + \infty - \infty + ...$ is undetermined

The Fresnel integral
	The function $\sin(t^2)$ does not have an integral that can be represented in terms of elementary functions.
		It does have an integral, since it is a continuous function. For example, we know from FTC 1 that
			$\displaystyle S(x) = \int_{0}^{x}\sin(t^2)dt$
			Satisfies $S'(t) = sin(t^2)$ and $\displaystyle \int \sin(t^2)dt = S(t)+C$

Find the Taylor series of $\displaystyle S(x) = \int_{0}^{x}sin(t^2)dt$. Explain why the radius of convergence is $+\infty$ and why can be sure that $S(x)$ equals its Taylor series for every value of $x$
	$\displaystyle \sin(x) = x -\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+...$
	$\displaystyle sin(t^2) = t^2 - \frac{(t^2)^3}{3!}+\frac{(t^2)^5}{5!}-\frac{(t^2)^7}{7!}+ ... = t^2 - \frac{t^6}{3!}+\frac{t^{10}}{5!}-\frac{t^{14}}{7!}+...$
	General anti-derivative $\to +C$
		$\displaystyle \int\sin(t^2)dt = \int t^2 - \frac{t^6}{3!}+\frac{t^{10}}{5!} - ... dt = \frac{t^3}{3}-\frac{t^7}{7\times 3!}+\frac{t^{11}}{11\times 5!}-\frac{t^{15}}{15\times 7!}+ ... +C$
	Specific anti-derivative $\to$ find C
	$\displaystyle \int_{0}^{x}\sin(t^2)dt = \frac{x^3}{3\times 1!}-\frac{x^7}{7\times 3!}+\frac{x^{11}}{11\times 5!}-...+C$
		To find $C \to$ plug in $x=0$
	  L.H.S $\displaystyle \to \int_{0}^{0}... = 0$
	  RHS = $0-0+0-0+...+C$
		$C=0$
	$\displaystyle S(x) = \frac{x^3}{3}-\frac{x^7}{7\times 3!}+\frac{x^{11}}{11\times 5!}-... = \sum_{n=0}^{\infty}(-1)^n\frac{x^{(4n+3)}}{(4n+3)(2n+1)!}$
	Radius of convergence is $+\infty$ because it is true for $\sin(x)$ and a variable change does not change radius of convergence

Once we have the Taylor series of $S(x)$, we can use it to analyse the function $S(x)$
Find $\displaystyle \lim_{x\to 0}\frac{S(x)}{x^4}$
$\displaystyle =\lim_{x\to 0}\frac{\frac{x^3}{3\times 1!}-\frac{x^7}{7\times 3!}+\frac{x^{11}}{11\times 5!}-...}{x^3}=\lim_{n\to 0}\frac{1}{3}-\frac{x^4}{7\times 3!} + \frac{x^8}{11\times 5!}-... = \frac{1}{3}$

We can often find the Taylor series centred at $a$ by starting with the Taylor series centred at 0
	$\displaystyle e^y = 1 + y + \frac{y^2}{2!}+\frac{y^3}{3!}+...$
	$\displaystyle e^x = e^{2+(x-2)} = e^2e^{x-2} = e^2\left[1+(x-2)+\frac{(x-2)^2}{2!}+\frac{(x-2)^3}{3!}+...\right]$
	$\displaystyle =e^2 + e^2(x-2)+e^2\frac{(x-2)^2}{2!} + e^2\frac{(x-2)^3}{3!} + ...$
	$\displaystyle =\sum_{n=0}^{\infty} e^2\frac{(x-2)^n}{n!}$

Euler's formula
	The imaginary unit $i$ is defined to be a number such that $i^2 = -1$ (it is not a real number because if x is real then $x^2 \geq 0$)
	Numbers of the form $a+bi$ are called complex numbers.

Show that, for all $x\in\mathbb{R}$
	$\displaystyle e^{ix}=cos(x)+isin(x)$
	$\displaystyle e^{ix} = 1+ix+\frac{(ix)^2}{2!}+\frac{(ix)^3}{3!} + ...$
	$\displaystyle =1+ix-\frac{x^2}{2!}-i\frac{x^3}{3!}+\frac{x^4}{4!}+i\frac{x^5}{5!}-\frac{x^6}{6!}-...$
	$\displaystyle =(1-\frac{x^2}{2!}+\frac{x^2}{4!}-\frac{x^6}{6!}+...)+ i(x-\frac{x^3}{3!}+\frac{x^5}{5!}-...)$
	$\displaystyle = \cos(x) + i(\sin(x))$
 
$\displaystyle e^{iπ}+1 = 0$

[[MATH 101 Discussion 11]]