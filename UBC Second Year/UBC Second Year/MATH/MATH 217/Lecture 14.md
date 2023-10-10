Basic property is linearity
	$\displaystyle \iint_R (af(x,y)+b(g(x,y)))dxdy$
	$\displaystyle =a\iint_R fdA + b\iint_R gdA,\text{  } a,b \in \mathbb{R}$

We can use FTC for computing double integrals

Partial integrals
	$\displaystyle g(y) = \int_{x=1}^{b} f(x,y)dx$ treat $y$ as a constant
Theorem:
$R = [a,b] \times [c,d]$
	$\displaystyle \iint_{R} fdA = \int_{y=c}^{d} \left[\int_{x=a}^{b} f(x,y)dx \right]dy$

Fubini's Theorem:
	We can do the integral in either order
		$\displaystyle \iint_{R} fdA = \int_{y=c}^{d}\left(\int_{x=a}^{b}f(x,y) dx\right)dy = \int_{x=a}^{b}\left(\int_{y=c}^{d}f(x,y) dy\right)dx$

