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
	The error of a numerical method is the absolute value of the difference between the exact solution and the numerical solution