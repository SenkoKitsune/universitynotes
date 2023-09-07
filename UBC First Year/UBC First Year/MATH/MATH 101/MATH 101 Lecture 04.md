Trig sub
In the substitution we have seen until now, we have chose u = u(x)
	We now substitute x = x(θ)

Rule of thumb
	Chose a substitution x = x(θ) which is a trig function of the new variable θ
	Apply the substitution rule
		$\displaystyle\int f(x)dx = \displaystyle\int f(x(θ))\displaystyle\frac{dx}{dθ}dθ$
	Express answer in terms of x by finding θ = θ(x) and/or using trig identities

To deal with $\displaystyle\sqrt{z^2-x^2}$, (a>0)
x = a sin(θ), dx = a cosθdθ
It's handy to know that 
$\displaystyle\sqrt{a^2-x^2} = \displaystyle\sqrt{a^2-a^2sin^2(θ)} = \displaystyle\sqrt{a^2(1-sin^2(θ))} = \displaystyle\sqrt{a^2}\displaystyle\sqrt{cos^2(θ)}= a|cosθ| = a cosθ$
	where we use the fact that cosθ >= 0 on $[-\displaystyle\frac{π}{2}, \displaystyle\frac{π}{2}]$

Recall trig identities
$sin(2θ) = 2cos(θ)sin(θ)$

Eg) Expess sin(2θ) in terms of x without using trig or inverse trig functions
	x = cos(θ), θ 
	$sin(2θ) = 2sin(θ)cos(θ)$
	$sin^2(θ) = 1-cos^(θ) = 1-x^2$
	$sin(θ) = +- sqrt{1-x^2}$

Compute $\displaystyle\int_{0}^{a}\sqrt{a^2-x^2}dx$ in two ways, using geometry and using suitable trig sub
1) area: y = $\displaystyle\sqrt{a^2-x^2} >= 0$
2) $y^2=a^2-x^2$
3) $x^2+y^2=a^2$ : circle of centre (0, 0) with radius a
	A circle is not a graph of a function
	It is a quarter of the total circle
		$\displaystyle\int_{0}^{a}\sqrt{a^2-x^2}dx$ = $\displaystyle\frac{1}{4}πa^2$

1) using trig sub
2) x = a sin(θ)
3) dx = a cos(θ)dθ
4) $\displaystyle\sqrt{a^2-x^2} = \displaystyle\sqrt{a^2-a^2sin^2(θ)}= \displaystyle\sqrt{a^2(1-sin^2(θ))} = \displaystyle\sqrt{a^2cos^2(θ)} = \displaystyle\sqrt{a}\displaystyle\sqrt{cos^2(θ)} = acos(θ)$
5) 0 = a sin(θ) -> θ = 0
6) a = a sin(θ) -> sin(θ) = 1, θ = $\displaystyle\frac{π}{2}$
7) $\displaystyle\int_{0}^{π/2} acos(θ)acos(θ)dθ= \displaystyle\int_{0}^{π/2} a^2cos^2(θ)dθ = a^2\displaystyle\int_{0}^{π/2} cos^2(θ)dθ = \displaystyle\frac{1}{4}πa^2$

For $\displaystyle\sqrt{x^2+a^2}$ or $\displaystyle\frac{1}{x^2+a^2}$
	x = a tanθ and dx = a sin<sup>2</sup>θ dθ
	$x^2+a^2 = a^2tan^2(θ) + a^2 = a^2(tan^2(θ) + 1) = a^2sec^2(θ)$

Compute $\displaystyle\int\frac{1}{\displaystyle\sqrt{x^2+1}}dx$
$x^2+1 = x^2 + 1^2 -> a = 1$
$x = tanθ, dx = sec^2(θ)dθ$\
$\displaystyle\int\frac{1}{\displaystyle\sqrt{x^2+1}}dx = \displaystyle\int\frac{1}{\displaystyle\sqrt{tan^θ+1}}* sec^2(θ)dθ = \displaystyle\int\frac{1}{\displaystyle\sqrt{sec^2(θ)}}* sec^2(θ)dθ=\displaystyle\int\frac{sec^2(θ)}{sec(θ)}dθ = \displaystyle\int sec(θ)dθ = ln(|tan(θ) + sec(θ)|) + C$
	$tan(θ) = x$, $sec(θ)$ -> $sec^2(θ) = tan^2(θ) + 1 = x^2+1$ -> $sec(θ) = \displaystyle\sqrt{x^2+1}$

To deal with $\displaystyle\sqrt{x^2-a^2}$, we let
	x = a sec(θ), dx = a sec(θ) tan(θ)
	$x^2-a^2 = a^2sec^2(θ) - a^2 = a^2(sec^2(θ)-1) = a^2tan^2(θ)$
	$\displaystyle\sqrt{x^2-a^2} = atan(θ)$

Compute $\displaystyle\int\frac{1}{\displaystyle\sqrt{x^2-16}}dx$
	x = a sec(θ) = 4 sec(θ)
	dx = a sec(θ)tan(θ) = 4tan(θ)
	$\displaystyle\sqrt{x^2-4^2} = \displaystyle\sqrt{4^2(sec^2(θ)-1)} = 4tan(θ)$
	$\displaystyle\int\displaystyle\frac{4sec(θ)tan(θ)}{4tan(θ)}d(θ) = ln(|tan(θ)+ sec(θ)) + C$
	=$ln(|\displaystyle\sqrt{\displaystyle\frac{x}{4}-1}+\displaystyle\frac{x}{4}|)+C$


Completing the square increases the usability of the method

Integration by parts
	In addition to direct integration, there are two main methods to find anti-derivatives. Substitution and by parts



Integration by parts $\displaystyle\int udv = uv - \displaystyle\int vdu$
Function u should have a convenient derivative
Function v' should have a convenient antiderivative

[[MATH 101 Lecture 05]]