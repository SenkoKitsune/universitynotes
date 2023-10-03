Integrating factors for exact equations

Suppose $\displaystyle M(x,y)+N(x,y)\frac{dy}{dx} = 0$ is not exact. Sometimes we can multiply an *integrating factor* $u(x,y)$ in the hopes of making it exact
	$\displaystyle u(x,y)(M(x,y)+u(x,y)N(x,y)\frac{dy}{dx}=0$
	$\displaystyle \tilde{M} = u(x,y)M(x,y) \Rightarrow \tilde{M}_y = \frac{\partial u}{\partial y}\cdot M + u\cdot M_y$
	$\displaystyle \widetilde{N}=u(x,y)N(x,y) \Rightarrow \widetilde{N}_x = \frac{\partial u}{\partial x}\cdot N + u\cdot N_x$
	In general, solving for $u(x,y)$ is easier than solving the original equation
		If $u=u(x)$
			$\displaystyle \frac{du}{dx}=\frac{M_y-N_x}{N}u$
				$\displaystyle \frac{\partial u}{\partial u}\cdot M(x,y)+uM_y=\frac{\partial u}{\partial x}\cdot N +uN_x$
				$\displaystyle \Rightarrow \frac{du}{dx}=u\left(\frac{M_y-N_x}{N}\right)$ Needs to be independent of $y$
				This is a separable equation
					$\displaystyle \int\frac{du}{u}=\int \left(\frac{M_y-N_x}{N}\right)dx$ to solve for $u=u(x)$
		If $u=u(y)$
			$\displaystyle \frac{du}{dy}= -\frac{M_y-N_x}{M}u$
				$\displaystyle \frac{\partial u}{\partial y}\cdot M + uM_y = \frac{\partial u}{\partial x}\cdot N + uN_x$
				$\displaystyle \Rightarrow \frac{du}{dy}=u\left(\frac{N_x-M_y}{M}\right)$ needs to be independent of x

