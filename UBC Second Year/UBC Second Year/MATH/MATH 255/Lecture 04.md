Linear equations and the integrating factor
	A first order differential equation is linear if it can be put into the following form:
		$y' = p(x)y=f(x)$
	Look for an integrating factor $μ(x)$, so that if we multiply both sides of $y' + p(x)y = f(x)$ by $μ(x)&, then the left hand side becomes
		$\displaystyle\frac{d}{dx}\left[ μ(x) y \right]$
	Multiply by $μ(x)$: $μ(x)y' + μ(x)p(x)y = f(x) μ(x)$
		We want left hand side to be
			$\displaystyle \frac{d}{dx}\left[ μ(x)y\right] = μ(x)y' + μ'(x)y$
			Look for $μ(x)$: $μ'(x) = μ(x)\cdot p(x)$ (separable differential equation)
				$\to \displaystyle \frac{dμ}{dx} = p(x)μ$
				$\to \displaystyle \int\frac{dμ}{μ} = \int p(x)dx$
				$\to \displaystyle \log |μ| = \int p(x)dx + C$
				$\to \displaystyle |μ| = e^C\cdot e^{\int p(x)dx}$
				$\to \displaystyle μ = e^C\cdot e^{\int p(x)dx}$
					Just need one integrating factor that works, so pick $\pm e^C = 1$

Steps to solve:
	1) Convert to: $y' + p(x)y = f(x)$
	2) Find the integrating factor $\displaystyle μ(x) = e^{\int p(x)dx}$
	3) Multiply by $μ(x)$: $μ(x)y' + μ(x)p(x)y = μ(x)f(x)$
	4) Write as: $\displaystyle \frac{d}{dx} (μ(x)y) = μ(x)f(x)$
	5) Integrate and solve:
		1) $\displaystyle μ(x) y = \int μ(x)f(x)dx + C$
		2) $\displaystyle y = \frac{1}{μ(x)}\left( \int μ(x)f(x)dx + C \right)$
		3) $\displaystyle y = \frac{1}{e^{\int p(x)dx}}\left(\int e^{\int p(x)dx}\cdot f(x)dx + C\right)$

The solution to any linear differential equation of the form $y + p(x)y = f(x)$ is:
	$\displaystyle y = e^{-\int p(x)dx}\left(\int e^{\int p(x)dx}f(x)dx + C\right)$

