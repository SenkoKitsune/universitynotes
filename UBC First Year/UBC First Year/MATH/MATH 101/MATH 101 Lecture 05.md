Numerical approximations for definite integrals
To use FTC:
1) We have an explicit formula for the function we want to integrate
2) the indefinite integral can be computed

Riemann sums
	approximating an integral by approximating areas of rectangles

Rectangle midpoint rule
Trapezoid trapezoidal rule
Parabola Simpson's rule
	3 points to fit a parabola

Formulas for numerical integration
Let Δx = (b-a)/n
Let x<sub>j</sub> = a + jΔx where j = 0,1,2,...,n

Right endpoint sum
$I \approx Δx\displaystyle\sum_{j=1}^{n}f(x_j) = Δx(0(f(0)) + f(x_1) + f(x_2) ...)$
Trapezoid rule
$I = Δx (\displaystyle\frac{1}{2}f(x_0) + f(x_1) + ... + f(x_{n-1}) + \displaystyle\frac{1}{2}f(x_n))$

Simpson's rule
n has to be even and at least 4
$I \approx Δx \displaystyle\frac{1}{3}(f(x_0) + 4f(x_1) + 2f(x_2) + 4f(x_3) + 2f(x_4) + ···+ 2f(x_{n−2}) + 4f(x{n−1}) + f(xn))$
Pattern: $\displaystyle\frac{1}{2}(1,4,2,4,2,...2,4,1)$

Trapezoid rule:
$Δx \displaystyle\frac{f(x_{j-1})+f(x_j)}{2}$

Eg) approx. arctan(2)
f(b) - f(a) = $\displaystyle\int_{a}^{b}f'(t)dt$ -> f(b) = f(a) + $\displaystyle\int_{a}^{b}f'(t)dt$
arctan(2) = arctan(0) + $\displaystyle\int_{0}^{2}\displaystyle\frac{d}{dt}arctan(2) = \int_{0}^{2}\displaystyle\frac{1}{1+t^2}dt$
[0,2] -> a = 0, b = 2 n = 4 Δx = $\displaystyle\frac{2-0}{n} = \frac{2}{4} = 0.5$
$x_0 = 0, x_1 = 0.5, x_2 = 1, x_3 = 1.5, x_4 = 2$
$\displaystyle f(x_0) = \frac{1}{1+0^2} = 1; f(x_1) = \frac{1}{1+0.5^2} = \frac{1}{1+1.25}; f(x_2) = \frac{1}{1+1^2}=\frac{1}{2}; f(x_3) = \frac{1}{1+1.5^2};f(x_4) = \frac{1}{1+2^2}=\frac{1}{5}$
Trapezoidal: add them together = 1.10385

Simpson's rule
$\displaystyle\frac{1}{3}[f(x_0)+4f(x_1)+2(f(x_2))+4(f(x_3))+f(x_4)]$

Error terms
Since A is an approximation to the unknown quantity Q. Then |Q-A| is the absolute error of the approximation and $\displaystyle\frac{|A - Q|}{|Q|}$ is the relative error

We can't hope to get an exact value for the error. We often make sure error doesn't exceed a certain threshold. We want to compute upper error

Trapezoid approximation using n points
	Absolute error is at most
	$\displaystyle\frac{M}{12}\frac{(b-a)^3}{n^2}$
	Where M is the maximum of |f''(x)| on the interval [a, b]

Simpson method using n points
	Absolute error is at most
		$\displaystyle\frac{L}{180}\frac{(b-a)^5}{n^4}$
		Where L is the maximum of $|f^4(x)|$ (the fourth derivative of f) on the interval [a, b]

[[MATH 101 Lecture 06]]
