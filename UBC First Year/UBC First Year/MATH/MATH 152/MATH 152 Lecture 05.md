General formula for computing the determinant

4x4 matrix
$\displaystyle\begin{bmatrix}a_1&a_2&a_3&a_4\\b_1&b_2&b_3&b_4\\c_1&c_2&c_3&c_4\\d_1&d_2&d_3&d_4\end{bmatrix} = a_1det(\displaystyle\begin{bmatrix}b_2&b_3&b_4\\c_2&c_3&c_4\\d_2&d_3&d_4\end{bmatrix}) - a_2det(\displaystyle\begin{bmatrix}b_1&b_3&b_4\\c_1&c_3&c_4\\d_1&d_3&d_4\end{bmatrix}) + a_3det(\displaystyle\begin{bmatrix}b_2&b_2&b_4\\c_1&c_2&c_4\\d_1&d_2&d_4\end{bmatrix}) - a_4det(\displaystyle\begin{bmatrix}b_1&b_2&b_3\\c_1&c_2&c_3\\d_1&d_2&d_3\end{bmatrix})$

Cross product
	special to vectors in R<sup>3</sup>
$\displaystyle\vec{a}\times\displaystyle\vec{b}$ = another vector in R<sup>3</sup>

$\displaystyle\vec{a}\times\displaystyle\vec{b} = det(\displaystyle\begin{bmatrix}\vec{i}&\vec{j}&\vec{k}\\a_1&a_2&a_3\\b_1&b_2&b_3\end{bmatrix})$

$\displaystyle\vec{i} = \displaystyle\begin{bmatrix}1\\0\\0\end{bmatrix}$, $\displaystyle\vec{j} = \displaystyle\begin{bmatrix}0\\1\\0\end{bmatrix}$, $\displaystyle\vec{k} = \displaystyle\begin{bmatrix}0\\0\\1\end{bmatrix}$

= $\displaystyle\begin{bmatrix}a_2b_3 - b_2a_3\\-(a_1b_3-b_1a_3)\\a_1b_2-b_1a_2\end{bmatrix} = (a_2b_3 - b_2a_3)\displaystyle\vec{i} + -(a_1b_3-b_1a_3)\displaystyle\vec{j} + (a_1b_2-b_1a_2)\displaystyle\vec{k}$

Geometry : relationship between $\displaystyle\vec{a}$, $\displaystyle\vec{b}$, and $\displaystyle\vec{a}\times\displaystyle\vec{b}$
1) $\displaystyle\vec{a}\times\displaystyle\vec{b}\perp \displaystyle\vec{a}$ &  $\displaystyle\vec{b}$
2)  $\displaystyle\vec{a}$, $\displaystyle\vec{b}$, and $\displaystyle\vec{a}\times\displaystyle\vec{b}$ satisfy the right hand rule
3) $||\displaystyle\vec{a}\times\displaystyle\vec{b}||$ = Area of parallelogram with $\displaystyle\vec{a}$ and $\displaystyle\vec{b}$ as sides

Properties
1) $\displaystyle\vec{a}\times\displaystyle\vec{b} = -\displaystyle\vec{b}\times\displaystyle\vec{a}$
2) $\displaystyle\vec{a}\times(\displaystyle\vec{b} + \displaystyle\vec{c}) = \displaystyle\vec{a}\times\displaystyle\vec{b} + \displaystyle\vec{a}\times\displaystyle\vec{c}$
3) $\displaystyle\vec{a}\times(s\displaystyle\vec{b}) = s(\displaystyle\vec{a}\times\displaystyle\vec{b})$, s is a scalar

In R<sup>3</sup>, dot product, cross product, and determinant are related via the following formula
$\displaystyle\vec{a} = \displaystyle\begin{bmatrix}a_1\\a_2\\a_3\end{bmatrix}$, $\displaystyle\vec{b} = \displaystyle\begin{bmatrix}b_1\\b_2\\b_3\end{bmatrix}$, $\displaystyle\vec{c} = \displaystyle\begin{bmatrix}c_1\\c_2\\c_3\end{bmatrix}$

$\displaystyle\vec{a}\dot(\displaystyle\vec{b}\times\displaystyle\vec{c}) = det(\displaystyle\begin{bmatrix}a_1&a_2&a_3\\b_1&b_2&b_3\\c_1&c_2&c_3\end{bmatrix})$
Proof:
$det(\displaystyle\begin{bmatrix}a_1&a_2&a_3\\b_1&b_2&b_3\\c_1&c_2&c_3\end{bmatrix})$ = $a_1 det(\displaystyle\begin{bmatrix}b_2 & b_3 \\ c_2 & c_3\end{bmatrix}) - a_2 det(\displaystyle\begin{bmatrix}b_1 & b_3 \\ c_1 & c_3\end{bmatrix}) + a_3 det(\displaystyle\begin{bmatrix}b_1 & b_2 \\ c_1 & c_2\end{bmatrix})$

= $\displaystyle\begin{bmatrix}a_1\\a_2\\a_3\end{bmatrix} \dot \displaystyle\begin{bmatrix}\begin{bmatrix}b_2 & b_3 \\ c_2 & c_3\end{bmatrix}\\-\begin{bmatrix}b_1 & b_3 \\ c_1 & c_3\end{bmatrix} \\ \begin{bmatrix}b_1 & b_2 \\ c_1 & c_2\end{bmatrix}\end{bmatrix}$

$\displaystyle\vec{b}\times\displaystyle\vec{c} = det(\displaystyle\begin{bmatrix}b_2 & b_3 \\ c_2 & c_3\end{bmatrix})\displaystyle\vec{i} - det(\displaystyle\begin{bmatrix}b_1 & b_3 \\ c_1 & c_3\end{bmatrix})\displaystyle\vec{j} + det(\displaystyle\begin{bmatrix}b_1 & b_2 \\ c_1 & c_2\end{bmatrix})\displaystyle\vec{k}$

We can use these operations & their geometric properties to help us describe basic objects in space or planes

Lines in R<sup>2</sup> 
	Parametric form
		A point q on L
		a direction $\displaystyle\vec{v}$
		use Q and $\displaystyle\vec{v}$ to write down a formula for points (x,y) on L in the following way
			1) identify 1 = $\displaystyle\begin{bmatrix}a\\b\end{bmatrix}$, a vector whose starting point is at (0,0)
			2) Identify an arbitrary point (x,y) on L with the base vector $\displaystyle\begin{bmatrix}x\\y\end{bmatrix}$
			3) $\displaystyle\begin{bmatrix}x\\y\end{bmatrix} = \displaystyle\begin{bmatrix}a\\b\end{bmatrix} + t \displaystyle\vec{v}$ : Parametric equation for L
				t is a parameter and a scalar
			It doesn't matter what t or $\displaystyle\vec{v}$ as long as $\displaystyle\vec{v}$ is parallel to L

[[MATH 152 Lecture 06]]