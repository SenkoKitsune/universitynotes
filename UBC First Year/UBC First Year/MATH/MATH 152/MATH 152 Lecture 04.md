$Proj_{c\displaystyle\vec{w}}\displaystyle\vec{v} = Proj{\displaystyle\vec{w}}\displaystyle\vec{v}$
	$c\neq0$

Determinant
	A matrix is a table of numbers
		$\displaystyle\begin{bmatrix}1 & 2 & 3\\0 & -5 & -6\end{bmatrix}$
		2x3 matrix: 2 rows and 3 columns
		$\displaystyle\begin{bmatrix} 1 & 2 & 3 \\ 0 &1 & 0\\0&0&1\end{bmatrix}$
		3x3 matrix

Determinant det(A) = a number
	A is an n x n matrix
		square matrix

n = 1,  det([a]) = a


n = 2
A = $\displaystyle\begin{bmatrix}a_1&a_2\\b_1&b_2\end{bmatrix}$
det(A) = $a_1b_2 - b_1a_2$

Properties
	1) det($\displaystyle\begin{bmatrix}a_1&a_2\\b_1&b_2\end{bmatrix})$ = det($\displaystyle\begin{bmatrix}a_1&b_1\\a_2&b_2\end{bmatrix}$)
	2) det($\displaystyle\begin{bmatrix}a_1&a_2\\b_1&b_2\end{bmatrix}$) = -det($\displaystyle\begin{bmatrix}b_1&b_2\\a_1&a_2\end{bmatrix}$)

Geometry behind the determinant formula
	$\displaystyle\vec{a} = \displaystyle\begin{bmatrix}a_1\\a_2\end{bmatrix}$
	$\displaystyle\vec{b} = \displaystyle\begin{bmatrix}b_1\\b_2\end{bmatrix}$

det($\displaystyle\begin{bmatrix}\displaystyle\vec{a}\\ \displaystyle\vec{b}\end{bmatrix}) = det(\displaystyle\begin{bmatrix}a_1&a_2\\b_1&b_2\end{bmatrix})$ = ±Area of parallelogram formed by the two vectors

Signs
	Get b from a by rotating an angle 0<sup>o</sup> < θ < 180<sup>o</sup> counter-clockwise
	Get a from b by rotating an angle 0<sup>o</sup> < θ < 180<sup>o</sup> counter-clockwise

n = 3
A = $\displaystyle\begin{bmatrix}a_1&a_2&a_3\\b_1&b_2&b_3\\c_1&c_2&c_3\end{bmatrix}$

det(A) = $a_1 det(\displaystyle\begin{bmatrix}b_2 & b_3 \\ c_2 & c_3\end{bmatrix}) - a_2 det(\displaystyle\begin{bmatrix}b_1 & b_3 \\ c_1 & c_3\end{bmatrix}) + a_3 det(\displaystyle\begin{bmatrix}b_1 & b_2 \\ c_1 & c_2\end{bmatrix})$
=$a_1(b_2c_3-b_3c_2) - a_2(b_1c_3-b_3c_1) + a_3(b_1c_2-b_2c_1)$

Geometry of the determinant for 3x3 matrices

A = $\displaystyle\begin{bmatrix}a_1 & a_2 & a_3 \\ b_1 & b_2 & b_3 \\ c_1 & c_2 & c_3 \end{bmatrix}$ = $\displaystyle\begin{bmatrix} \displaystyle\vec{a} \\ \displaystyle\vec{b} \\ \displaystyle\vec{c}\end{bmatrix}$

= ±volume of parallelepipedal with sides $\displaystyle\vec{a}$, $\displaystyle\vec{b}$, $\displaystyle\vec{c}$
Signs:
	If  $\displaystyle\vec{a}$, $\displaystyle\vec{b}$, $\displaystyle\vec{c}$ satisfy the right-hand rule, then det(A) is positive

[[MATH 152 Lecture 05]]