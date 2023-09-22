Euler's method
	Sometimes we cannot solve (first order) differential equations analytically
	We can calculate numerical solutions to the differential equation
		$\displaystyle \frac{dy}{dt}=f(t,y), y(t_0)=y_0$
	Using the following iteration method
		$y_1 = y_0 + f(t_0,y_0)h$
		$y_2 = y_1 + f(t_1,y_1)h$
		$\vdots$
		$y_{i+1}=y_i + f(t_i,y_i)h$
		Where $y_i = y(t_i)$ and $h = t_{i+1} - t_i$. If you want to approximate $y(T)(T > t_0)$ using $N$ steps, then
			$\displaystyle h = \frac{h-t_0}{N}$.
			In this way, $y(t_N) = y(T)$

Error estimate:
	The error of a numerical method is the absolute value of the difference between the exact solution and the numerical solution.
	We can prove that for Euler's method, we are guaranteed that Error $\leq c_1h$ for some constant $c_1$ and so this is called a *first-order method*
		- Improved Euler: Error $\leq c_2h^2 \leftarrow$ 2nd order method
		- Runge-Kutta (RK4): Error $\leq c_3h^4 \leftarrow$ 4th order method

Second order linear ODEs
	A second order linear ODE is an equation for $y(x)$ of the form
		$a(x)y^n+b(x)y\prime +c(x)y = g(x)$
		where $a(x) \neq 0$. If we divide by $a(x)$ we have the form
			$y^n + p(x)y\prime + q(x)y = f(x)$
			Which is called homogenous if $f(x) = 0$ and non-homogenous if $f(x) \neq 0$

Principle of superposition
	Suppose $y_1$ and $y_2$ are two solutions of the homogenous equation
		$y^n+p(x)y\prime + q(x)y=0$
		Then $y(x) = c_1y_1(x) + c_2y_2(x)$ is also a solution

Let $L(y) = y\prime\prime + p(x)y\prime + q(x)y$ be an operator
	An operator acts on a function to produce another function
	$L(y_1) = y_1\prime\prime + p(x)y_1\prime + q(x)y_1 = 0 \Rightarrow L(x_1) = 0$
	$L(y_2) = y_2\prime\prime + p(x)y_2\prime + q(x)y_2 = 0 \Rightarrow L(x_2) = 0$
	Because $L(x)$ is an operator associated with the linear ODE: $y\prime\prime + p(x)y\prime + q(x)y$, $L(x)$ is also linear
		$L(c_1y_1+c_2y_2) = c_1L(y_1) + c_2L(y_2) = 0$
		If $y(x) = c_1y_1 + c_2y_2 \Rightarrow L(y(x)) =  y\prime\prime + p(x)y\prime + q(x)y = 0$
			So $y(x)$ solves the ODE
			You can also check by putting $y(x) = c_1y_1(x) + c_2y_2(x)$ into both sides of the ODE

Existence and uniqueness
	Suppose $p,q,f$ are continuous on some interval $I$, with $x_0 \in \mathbb{I}$, then
		$y\prime\prime + p(x)y\prime + q(x)y = f(x)$
		has only one solution $y(x)$ defined on the same interval $I$ satisfying the initial conditions
			$y(x_0) = y_0, y\prime(x_0)=y_1$
		*We need two initial conditions to determine a particular solution to a second order ODE*

General solutions
		Let $p,q,f$ be continuous functions. If $y_1(x)$ and $y_2(x)$ are two linearly independent solutions of the homogenous equation
			 $y\prime\prime + p(x)y\prime + q(x)y = 0$
		Then the general solution is
			$y(x) = c_1y_1(x) + c_2y_2(x)
		In other words, every solution will have the form $y(x) = c_1y_1(x) + c_2y_2(x)$

Reduction of order
	If we know one solution, $y_1(x)$ to the homogenous DE
		 $y\prime\prime + p(x)y\prime + q(x)y = 0$
		Then we can find a second solution of the form $y_2(x)=y_1(x)v(x)$ by plugging in $y_2(x)$ into the differential equation and solving for $v(x)$

