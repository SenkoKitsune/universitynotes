For first order differential equations of the form $y' = f(x)$ we can simply integrate to find the solution of $\displaystyle y  = \int f(x) dx$

A general solution for a given DE is a family of functions that captures all possible solutions
	a solution with an arbitrary constant

An *Initial Value Problem* is a differential equation subject to an initial condition
	$y' = f(x), y(x_0) = y_0$
	$\displaystyle y = \int_{x_0}{x}f(t)dt + y_0$ $\longleftarrow$ particular solution
	A particular solution is a solution satisfying an initial value problem
		Solution with no arbitrary constant

Separable equations

If a first order differential equation is of the from
	$\displaystyle \frac{dy}{dx}=f(x)g(y)$
	then it is called a separable differential equation and can be solved by separation of variables (integration)
	$\displaystyle \frac{dy}{dx}=f(x)g(y)$
	$\displaystyle\frac{1}{g(y)}y'(x)=f(x)$
	$\displaystyle\int\frac{1}{g(y)}y'(x)dx = \int f(x)$
	Let $y = y(x) \to dy = y'(x)dx$
	$\displaystyle\int\frac{1}{g(y)}dy=\int f(x)dx$

Solving a separable equation is only as difficult as solving the integrals $\displaystyle \int\frac{1}{g(y)}dy$ and $\displaystyle\int f(x)dx$
