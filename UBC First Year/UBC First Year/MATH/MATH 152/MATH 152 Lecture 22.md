Operations on matrices
1) Transpose
	$\displaystyle A = \begin{bmatrix}a_{ij}\end{bmatrix}_{m\times n}$
	$\displaystyle A^T = \begin{bmatrix}b_{ij}\end{bmatrix}$
	$b_{ij} = a_{ji}$

Properties:
1) $\displaystyle (A^T)^T = A$
2) $(A+B)^T = A^T + B^T$
3) $(sA)^T = sA^T$

ex) $\displaystyle \vec{v} = \begin{bmatrix} 1\\2\\3\end{bmatrix}$
	$\displaystyle \vec{v}^T = \begin{bmatrix}1 & 2 & 3\end{bmatrix}$
	$\displaystyle \vec{w} = \begin{bmatrix}4\\5\\6\end{bmatrix}$
We can express dot product in terms of matrix multiplications
	$\displaystyle \vec{v}^T\vec{w} = \vec{v}\cdot\vec{w}$
$\displaystyle \vec{v}\cdot\vec{w} = \vec{v}^T\vec{w}$
$\displaystyle \vec{v},\vec{w} \in R^n$



$\displaystyle (AB)^T = B^TA^T$.
	$\displaystyle (A_{m\times n}B_{n\times l})^T = B_{l\times n}^TA_{n\times m}^T$

ex) $\displaystyle A = \begin{bmatrix} 1 & 2 \\ 3 & 4\end{bmatrix}_{2\times 2}, B = \begin{bmatrix}1 & 2 & 3\\4 & 5 & 6\end{bmatrix}_{3\times 3}$

$\displaystyle AB = \begin{bmatrix} c_{11} & c_{21} & c_{31} \\ c_{12}  & c_{22} & c_{23}\end{bmatrix}_{2\times 3}$
$\displaystyle ij$ = the $i-th$ entry of $\displaystyle (AB)^T$
($j-th$ row of A)($i-th$ column of B)
$ij-th$ entry of $\displaystyle B^TA^T$
	=($j-th$ row of A) $\cdot$ ($i-th$ column of B)

The inverse of a matrix
	Def: $\displaystyle A_{n\times n}$ is a $\displaystyle n\times n$ matrix, $\displaystyle A^{-1}$ is the $n\times n$ matrix that $AA^{-1} = I_n, A^{-1}A = I_n$

Note very square matrix has an inverse
Eg) $\displaystyle \begin{bmatrix}2 & 0\\0 &  0\end{bmatrix}$ does not admit an inverse

Why is $A^{-1}$ useful?
1) Solve for equations
	Eg) $A\vec{x}=\vec{b}$
		$A^{-1}(A\vec{x}) = A^{-1}\vec{b}$
		$= I\vec{x} = A^{-1}\vec{b} \to \vec{x} = A^{-1}\vec{b}$
2) Solve for equation with unknowns being matrices
	Eg) $AXA+B = 0$,  X is an $n\times n$ matrix, A is invertible
		$AXA = -B$
		$A^{-1}(AXA)A^{-1}=-A^{-1}BA^{-1}$
		$IXI = -A^{-1}BA^{-1}$
3) If $A^{-1}$ exists, then $A^{-1}$ represents the inverse linear transformation represented by $A$
	$Rot_θ \leftrightarrow \begin{bmatrix} cosθ & -sinθ \\ sinθ & cosθ\end{bmatrix}$
	$Rot_{(-θ)} \leftrightarrow \begin{bmatrix}cos(-θ) & -sin(-θ) \\ sin(-θ) & cos(-θ)\end{bmatrix}$
	$Rot_{(-θ)} \circ Rot_θ = I = Rot_θ\circ Rot_{(-θ)}$.
		$Rot_θ$ and $Rot_{(-θ)}$ are mutually inverse to each other, so are their matrices

How to find $A^{-1}$?
	If $A = \begin{bmatrix}A & B \\C & D\end{bmatrix}$
		If $\det{(A)} = AD - BC \neq 0$,
			Then $\displaystyle A^{-1} = \frac{1}{\det(A)}\begin{bmatrix}D & -B \\ -C & A\end{bmatrix}$

Check:
	$\displaystyle \begin{bmatrix}A & B\\C&D\end{bmatrix}(\frac{1}{\det(A)})\begin{bmatrix}D & -B \\ -C &A\end{bmatrix}$
	$\displaystyle = \frac{1}{\det(A)}\begin{bmatrix}A&B\\C&D\end{bmatrix}\begin{bmatrix}D&-B\\-C&A\end{bmatrix} = \frac{1}{\det(A)}\begin{bmatrix}AD-BC & 0//0&-BC+AD\end{bmatrix}$
	$\displaystyle = \begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix}$

In general, for an $n\times n$ matrix A, $A^{-1}$ exists if and only if $\det(A) \neq 0$ ad there is a formula for $A^{-1}$ involving $\det(A)$

[[MATH 152 Lecture 23]]