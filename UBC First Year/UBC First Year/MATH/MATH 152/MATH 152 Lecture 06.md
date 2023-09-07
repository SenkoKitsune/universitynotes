Lines and planes
Equation form $ax + by = C$
Coefficient vector is $\perp$ to the line L
	Normal vector is coefficient of X and Y
How to find the equation form:
	input:
		1) a point $\displaystyle\begin{bmatrix}x_o\\y_x\end{bmatrix}$
		2) a normal vector $\displaystyle\vec{n} = \displaystyle\begin{bmatrix}a\\y_b\end{bmatrix}$
			$\displaystyle\vec{n}\perp L$
	(x, y)
	$\displaystyle\begin{bmatrix}x-x_o\\y-y_o\end{bmatrix}\perp\displaystyle\vec{n}$

$\displaystyle\begin{bmatrix}x-x_o\\y-y_o\end{bmatrix} \dot \displaystyle\begin{bmatrix}a\\b\end{bmatrix} = 0$
=$a(x-x_o) + b(y-y_o)$
$a_x+b_y - ax_o -by_o = 0$
$ay+by = ax_o + by_o$
	$ax_o + by_o = C$

Parametric form to equation form
$\displaystyle\begin{bmatrix}x\\y\end{bmatrix} = \displaystyle\begin{bmatrix}2\\1\end{bmatrix} + t\displaystyle\begin{bmatrix}3\\1\end{bmatrix}$

$\displaystyle\begin{bmatrix}2\\1\end{bmatrix}$ = point on L

$t\displaystyle\begin{bmatrix}3\\1\end{bmatrix}$ = directional vector

To equation form:
	 Need :
	1) a point, $\displaystyle\begin{bmatrix}2\\1\end{bmatrix}$
	2) a normal vector $\displaystyle\vec{n}$ such that $\displaystyle\vec{n}\cdot\displaystyle\vec{v} = 0$

In general $\displaystyle\vec{v} = \displaystyle\begin{bmatrix}a\\b\end{bmatrix}$, then $\displaystyle\begin{bmatrix}b\\-a\end{bmatrix} \perp \displaystyle\begin{bmatrix}a\\b\end{bmatrix}$ since $\displaystyle\begin{bmatrix}a\\b\end{bmatrix}\dot\displaystyle\begin{bmatrix}b\\-a\end{bmatrix} = 0$

$\displaystyle\begin{bmatrix}x-2\\y-1\end{bmatrix}\dot\displaystyle\begin{bmatrix}1\\-3\end{bmatrix} = 0$
$1(x-2) + (-3)(y-1) = 0$
$x-3y = -1$


Equation to parametric form
$x-y = -2$
$\displaystyle\vec{n} = \displaystyle\begin{bmatrix}1\\-1\end{bmatrix}$ = direction vector $\displaystyle\vec{v} = \displaystyle\begin{bmatrix}-1\\-1\end{bmatrix}$
To find a point on L, pick a x value and solve for y
Point (0, 2)
x=0, 0 - y = -2, y = 2

Parametric form
$\displaystyle\begin{bmatrix}x\\y\end{bmatrix} = \displaystyle\begin{bmatrix}0\\2\end{bmatrix} + t\displaystyle\begin{bmatrix}-1\\-1\end{bmatrix}$

Planes in R<sup>3</sup>

Need: 
1) a point on the plain
	$\displaystyle\vec{q} = \displaystyle\begin{bmatrix}x_o\\y_o\\z_o\end{bmatrix}$
2) two directional vectors (not colinear)
	$\displaystyle\vec{v}$ & $\displaystyle\vec{w}$
	$\displaystyle\begin{bmatrix}x\\y\\z\end{bmatrix}-\displaystyle\vec{q} = s\displaystyle\vec{v} + t\displaystyle\vec{w}$

Parametric form:
	$\displaystyle\begin{bmatrix}x\\y\\z\end{bmatrix} = \displaystyle\vec{q}+ s\displaystyle\vec{v} + t\displaystyle\vec{w}$
		not unique since we may pick different, $\displaystyle\vec{q}$, $\displaystyle\vec{v}$ & $\displaystyle\vec{w}$

Equation form
Input:
	1) 1 normal vector $\displaystyle\begin{bmatrix}a\\b\\c\end{bmatrix}$
	2) a point $\displaystyle\begin{bmatrix}x_o\\y_o\\z_o\end{bmatrix}$
$ax + by + cz = d$

$\displaystyle\vec{n} = \displaystyle\begin{bmatrix}a\\b\\c\end{bmatrix} \perp$ plane

$\displaystyle\begin{bmatrix}x-x_o\\y-y_o\\z-z_o\end{bmatrix} \dot \displaystyle\begin{bmatrix}a\\b\\c\end{bmatrix} = 0$

$a(x-x_o) + b(y-y_o) + c(z-z_o) = 0$
$ax + by + cz = ax_o + by_o + cz_o$


Trick
$\displaystyle\vec{n} = \displaystyle\vec{v}\times\displaystyle\vec{w}$

[[MATH 152 Lecture 07]]