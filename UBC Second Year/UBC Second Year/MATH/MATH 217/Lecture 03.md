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
		