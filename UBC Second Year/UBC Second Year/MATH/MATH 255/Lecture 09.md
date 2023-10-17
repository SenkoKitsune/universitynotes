Suppose we have the differential equation:
$ay\prime\prime + by\prime + cy = 0$,
where $a,b,c$ are constants and $a \neq 0$. Try the solution $y = e^{rx}$ to obtain
	$ar^2e^{rx} + bre^{rx} + ce^{rx} = 0$
and divide through by $e^{rx}$ to obtain the characteristic equation
	$ar^2+br_c = 0$
which has roots
	$\displaystyle r_1,r_2 = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$
	1) If $b^2-4ac > 0$, then $r_1$ and $r_2$ are real and distinct and the general solution is
		$\displaystyle y = c_1e^{r_1x}+c_2e^{r_2x}$
	2) If $b^2-4ac = 0$, then $r_1 = r_2$ and the general solution is
		$\displaystyle y=c_1e^{r_1x}+c_2xe^{r_1x}$
	3) If $b^2-4ac < 0$, then $r_1$ and $r_2$ are complex and of the form $r_1,r_2 = \alpha \pm i\beta$
		$y = c_1e^{\alpha x}\cos(\beta x) + c_2e^{\alpha x}\sin(\beta x)$



Complex:
$\mathbb{C} = \left\{a+bi\mid a_0b \in\mathbb{R}\right\}$
	$i = \sqrt{-1} \to i^2 = -1$

Euler's formula 
	$e^{it} = \cos(t)+i\sin(t)$
	Taylor series : $\displaystyle f(t) = f(0) + f\prime(0)t+f\prime\prime(0)\frac{t^2}{2!} + f\prime\prime\prime(0)\frac{t^3}{3!} + \dots$
		$f(t) = e^{it}$
		$f\prime(t) = ie^{it}$
		$f\prime\prime(t) = i^2e^{it} = -e^{it}$
		$f\prime\prime\prime = -ie^{it}$
		$f^4(t) = -i^2e^{it} = e^{it}$

Suppose the equation $ay\prime\prime + by\prime + cy = 0$ has the characteristic equation $ar^2+br+c=0$ that has complex roots, so
	$\displaystyle r_1,r_2 = \frac{-b \pm \sqrt{b^2-4ac}}{2a} = \alpha \pm i\beta$
		$r_1 = \alpha + i\beta, r_2 = \alpha - i\beta$
		So two solutions
			$\displaystyle y_1(x) = e^{\alpha + i\beta}x = e^{\alpha x}(\cos(\beta x) + i\sin(\beta x))$
			$\displaystyle y_2(x) = e^{\alpha - i\beta}x = e^{\alpha x}(\cos(\beta x) - i\sin(\beta x))$
				These solutions are complex, we need real solutions
					$\displaystyle y_3 = \frac{y_1(x)+y_2(x)}{2} = e^{\alpha x}\cos{\beta x}$
					$\displaystyle y_4 = \frac{y_1(x)-y_2(x)}{2} = e^{\alpha x}\sin{\beta x}$
					$y_3(x)$ and $y_4(x)$ are linearly independent so
						General solution: $\displaystyle y(x) = c_1e^{\alpha x}\cos(\beta x) + c_2e^{\alpha x}\sin(\beta x)$
