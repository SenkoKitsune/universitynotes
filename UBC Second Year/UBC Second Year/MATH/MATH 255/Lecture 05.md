Exact equations

The following equation is not separable and not linear
	$\displaystyle (y+2x)+(x-3y^2)\frac{dy}{dx}=0$
	But what if we can find a function $\phi(x,y)$
		$\displaystyle \frac{d}{dx}\phi(x,y) = \frac{\delta \phi}{\delta \phi}+\frac{\delta\phi}{\delta y}\frac{dy}{dx} = 0$
		Then the solution would be $\phi(x,y) = C$
			Here: $\displaystyle \frac{\delta φ}{\delta x}= y+2x$
			$\displaystyle \frac{\delta φ}{\delta y} = x-3y^2$
			So if we could find a $φ(x,y)$ such that the above equations were satisfies, then the solution would be $φ(x,y)  = C$. Here, $φ(x,y) = xy+x^2-y^3$ is one such function, so the soltuion is $xy+x^2-y^3 = C$

A differential equation of the form
	$M(x,y) + N(x,y)\frac{dy}{dx} = 0$
	is called exact if tthere is a function $\phi(x,y)$ such that $M(x,y)=\phi_x$ and $N(x,y)=\phi_y$. In this case the function $\phi(x,y)$ is called a potential. For exact equations, the solution is given by
		$\phi(x,y) = C$
	A differential equation of the form
		$\displaystyle M(x,y) + N(x,y)\frac{dy}{dx}=0$
		is exact if and only if
			$M_y(x,y) = N_x(x,y)$
			That is, there exists a function $\phi(x,y)$ such that $M(x,y)=\phi_x$ and $N(x,y)=\phi_y$
		This is because
			$\displaystyle\frac{\delta^2φ(x,y)}{\delta x \delta y}=\frac{\delta^2φ(x,y)}{\delta y \delta x}$
				$M_y = φ_{xy} = φ_{yx} = N_x$

To solve an exact eqatuion, integrate one of 
	$\phi_x(x,y) = M(x,y)$ or $\phi_y(x,y) = N(x,y)$ and use the other equation to solve the unknown function
		Integrate $φ_x = M(x,y)$
			$φ = \int M(x,y)dx + h(y)$
				$M(x,y) = Q(x,y)$ and $h(y)$ = unknown function of y
		Differentiate and use $φ_y = N$ 