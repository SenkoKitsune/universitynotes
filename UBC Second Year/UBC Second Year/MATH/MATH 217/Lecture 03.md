Cross product for $\vec{A}, \vec{B}$ in $\mathbb{R}^3$
	$\vec{A} \times \vec{B}$ is another vector

| Geometric                                                                                              | Algebraic                   |
| ------------------------------------------------------------------------------------------------------ | --------------------------- |
| Direction of $\vec{A} \times \vec{B}$ is perpendicular to both $\vec{A}$ and $\vec{B}$, satisfying RHR | $\vec{A} = <a_1,a_2,a_3>$   |
| Magnitude in $\mid \vec{A}\times\vec{B}\mid = \mid\vec{A}\mid\mid{B}\mid\sinθ$                         | $\vec{B} = <b_1,b_2,b_3>$   |
| $\vec{A}\times\vec{B} = \vec{0} \to \vec{A}\parallel\vec{B}$                                           | $\vec{A}\times\vec{B} = (a_2b_3-b_2a_3)\hat{i} -(a_1b_3-b_1a_3)\hat{j}+(a_1b_1-a_2b_1)\hat{k}$ |                                                                                                       |                             |

Cross product is not commutative
	$\vec{A}\times\vec{B} = -\vec{B}\times\vec{A}$
	$\vec{A}\times(\vec{B}+\vec{C}) = \vec{A}\times\vec{B} + \vec{A}\times\vec{C}$

Cross product is not associative
	$\vec{A}\times(\vec{B}\times\vec{C}) \neq (\vec{A}\times\vec{B})\times\vec{C}$
		If it were true it would hold
			If $\vec{B} = \vec{C}$
				$\vec{A}\times(\vec{B}\times\vec{B}) =? (\vec{A}\times\vec{B}) \times \vec{B}$
				$\vec{0} = ?$

If scalar $\vec{A}\cdot(\vec{B}\times\vec{C})$ is the $\pm$ volume of the parallel piped spanned by $\vec{A},\vec{B},\vec{C}$
	$\vec{A}\cdot(\vec{B}\times\vec{C}) = (a_1\hat{i} + a_2\hat{j}+ a_3\hat{k})\cdot \begin{bmatrix}\hat{i} & \hat{j} & \hat{k} \\ b_1 & b_2 & b_3 \\ c_1 & c_2 & c_3 \end{bmatrix}$
		$= \begin{bmatrix}a_1 & a_2 & a_3 \\ b_1 & b_2 & b_3 \\ c_1 & c_2 & c_3 \end{bmatrix}$
	$\vec{A}\cdot (\vec{B}\times\vec{C}) = (\vec{A}\times\vec{B})\cdot\vec{C}$, not $(\vec{A}\cdot\vec{B})\times \vec{C}$

One way to think of dot projects is in terms of projections
	The distance is the scalar projection of $\vec{B}$ in the direction of $\vec{A}$, aka the component of $\vec{B}$ in the direction of $\vec{A}$
		$\displaystyle comp_{\vec{A}}\vec{B}=\cos{θ}|\vec{B}| = \frac{|vec{A}\cdot\vec{B}}{|\vec{A}|}$
	Vector projection of $\vec{A}$ in the direction of $\vec{B}$
		$\displaystyle proj_{\vec{B}}\vec{A} = \left (\frac{\vec{A}\cdot\vec{B}}{|\vec{B}|} \right)\frac{\vec{B}}{|\vec{B}|} = \frac{\vec{A}\cdot\vec{B}}{\vec{B}\cdot\vec{B}}\vec{B}$

Equations of lines and planes in $\mathbb{R}^3$

Lines:
	Can be given by a point the line passes through and a direction
		Point: $(x_0,y_0,z_0)$
		$\vec{V} = <a,b,c>$
			$\vec{r}(t) = \vec{r_0}+t\vec{v}$
			$=<x_0,y_0,z_0> + t<a,b,c>$
			$= <x_0+ta, y_0+tb, z_0+tc>$
				$\vec{r}(t)$ is a parametric equation of the line (not unique)
					Component form:
						$x(t) = x_0+ta$
						$y(t) = y_0+tb$
						$z(t) = z_0 + tc$

Planes:
	A plane in $\mathbb{R}^3$ is determined by a point $(x_0,y_0,z_0)$ on it and a normal vector $\vec{N} = <a,b,c>$
		A point $(x,y,z)$ lies in $P$
			1) $\vec{B} \perp <x-x_0, y-y_0, z-z_0>$
			2) $0 = \vec{N}\cdot<x-x_0, y-y_0, z-z_0>$
			3) 0 = $a(x-x_0)+b(y-y_0)+c(z-z_0)$
				Can rewrite as
					$ax+by+c_z = d$
						$d = ax_0+by_0+cz_0$

