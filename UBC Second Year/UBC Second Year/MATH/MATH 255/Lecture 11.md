We want to find a general solution to the following 2nd order nonhomogeneous ODE
	$L[y] = A(t)y\prime\prime + B(t)y\prime + C(t)y = f(t)$ (1)
		Where $f(t) \neq 0$. Unlike the homogeneous ODE $L[y] = 0$, a linear combination of 2 solutions of (1) may not be a solution
			If $y_1$ and $y_2$ are solutions of (1), then $w(t) = y_1(t)-y_2(t)$ solves
				$L[w] = 0$
					$A(t)w\prime\prime + B(t)w\prime + C(t)w=0$
						$L[y_1] = f(t)$ & $L[y_2] = f(t)$
				From before, $L$ is a linear operator, of if $w(t) = y_1(t)-y_2(t)$
					$L[w] = L[y_1-y_2] = L[y_1]-L[y_2] = f(t)-f(t) = 0$
						So $w(t)$ solves $L[w] = 0$
