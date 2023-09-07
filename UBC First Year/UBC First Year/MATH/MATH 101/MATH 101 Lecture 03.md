Substitution

Linear change of variables

eg) Find $\displaystyle\int e^{3x+2}dx$
	We want all function whose derivative is $e^{3x+2}$
	We know $\displaystyle\int e^u du = e^u + C$
	Check $\displaystyle\frac{d}{dx} e^{3x + 2} = e^{3x+2} * 3$
	Check$\displaystyle\frac{d}{dx} \displaystyle\frac{e^{3x + 2}}{3} = e^{3x+2}$
	Answer: $\displaystyle\frac{e^{3x+2}}{3} + C$

Call 3x+2: u

u = 3x + 2
du = 3dx
dx = du/3


Find the derivatives of e<sup>x<sup>2</sup></sup> and g(x) = sin<sup>4</sub>(x)

$f(x) = e^{x^2}$, $f'(x) = e^{x^2}3x^2$
So: $\displaystyle\int e^{x^2}3x^2dx = e^{x^2}$
$g(x) = sin^4(x)$, $g'(x) = 4sin^3(x) cos(x)$
So: $\displaystyle\int 4sin^3(x) cos(x)dx =  sin^4(x)$

Chain rule: substitution is chain rule going backwards

Make sure to convert all variables into the new variable before proceeding 

How to substitute
Never substitute u = x
If you see function and the derivative of the function in the integral
	substitute u for the function
Look for a factor in the integrand that is a function with an argument that is more complicated than just x

eg) Evaluate $\displaystyle\int x\sqrt{2x^2+3}dx$
	u - $2x^2+3$

eg)
$\displaystyle\int_{1}^{e} f(x) = 4$, calculate $\displaystyle\int_{0}^{1}f(e^x)e^xdx$
	u = e<sup>x</sup>

Trigonometric integrals
eg) compute $\displaystyle\int tan(x)dx = \displaystyle\int \displaystyle\frac{sin(x)}{cosx}dx$
	u = cos(x)
		 u = sin(x) does not work because u' = cos(x) appears in the denominator
	= -$\displaystyle\int \displaystyle\frac{-sin(x)}{cos(x)}dx$
	=$- \displaystyle\int \displaystyle\frac{1}{u}du = -log|cos(x)| + C$

When either the power of sin or the power co cos (or both) is odd
	Suppose the power of sin is odd ( the case where cos is odd is similar exchanging the roles)
	Split one sin from the rest( $sin^7(x)$ = $sin^6(x)sin(x)$)
	For the remaining even power of sin, write it as a power of $sin^2$ ($sin^6(x) = sin^2(x)^3)
	Use the key trig identity to rewrite $sin^2(x) = 1-cos^2(x)$
	Substitute u = cos(x) and use algebra to solve the resulting integral

Both are even
Use the double angle formula to obtain a simpler trig integral in terms of 2x
$sin(x)cos(x) = \displaystyle\frac{sin(2x)}{2}$
$sin^2(x) = \displaystyle\frac{1-cos(2x)}{2}$
$cos^2(x) = \displaystyle\frac{1+cos(2x)}{2}$


[[MATH 101 Discussion 03]]