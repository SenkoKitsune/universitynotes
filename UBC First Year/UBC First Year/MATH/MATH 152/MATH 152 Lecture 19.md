Reflection about a line L = {$t\vec{a} | t\in R$}

$\displaystyle Ref(\vec{v}) = 2Proj_{\vec{a}}\vec{v} - \vec{v}$

We can write the matrix for reflection using this formula

$\displaystyle \vec{a} = \begin{bmatrix}a_1\\a_2\end{bmatrix}$
$\displaystyle Ref(\vec{v}) = \begin{bmatrix}\displaystyle\frac{2a_1^2}{a_1^2+a_2^2}-1 && \displaystyle\frac{2a_1a_2}{a_1^2+a_2^2} \\ \displaystyle\frac{2a_1a_2}{a_1^2+a_2^2} && \displaystyle\frac{2a_2^2}{a_1^2+a_2^2}-1 \end{bmatrix}$


General trick
	Given $T\cdot R^n \to R^m$ is a linear transformation, we want the matrix of T
		$\displaystyle A = \begin{bmatrix}a_{ij}\end{bmatrix}\displaystyle_{m\times n}$
		
$\displaystyle\begin{bmatrix}\displaystyle x_1\\x_2\\x_3\\...\\x_n\end{bmatrix} = A\begin{bmatrix}x_1\\x_2\\x_3\\...\\x_n\end{bmatrix}$

$= \begin{bmatrix}a_{11}x_1 + a_{12}x_2+...+a_{1n}x_n \\ a_{21}x_1 + a_{22}x_2 + ... + a_{2n}x_n \\ ... \\ a_{m1}x_1 + a_{m2}x_2 + ... + a_{mn}x_n  \end{bmatrix}$
Linear transformation, the its matrix
$\displaystyle A = \begin{bmatrix} 1 & 1 & & 1 \\ T(\vec{e_1}) & T(\vec{e_2}) & ... & T(\vec{e_n}) \\ 1 & 1 & & 1 \end{bmatrix}$

[[MATH 152 Lecture 20]]