Matrix multiplication
Matrix $m\times n$ matrix A = 
	$\displaystyle\begin{bmatrix}a_{11}&&a_{12}&&...&&a_{1n}\\a_{21}&&a_{22}&&...&&a_{2n}\\a_{m_1}&&a_{m2}&&...&&a_{mn}\end{bmatrix}$
Addition of two matrices of the same size
	Def A = $\begin{bmatrix}a_{ij}\end{bmatrix}_{m\times n}$ and B = *$\begin{bmatrix}b_{ij}\end{bmatrix}_{m\times n}$
		A + B = $\begin{bmatrix}a_{ij} + b_{ij}\end{bmatrix}_{m\times n}$

Subtraction of two matrices of the same size
	Def A = $\begin{bmatrix}a_{ij}\end{bmatrix}_{m\times n}$ and B = *$\begin{bmatrix}b_{ij}\end{bmatrix}_{m\times n}$
		A - B = $\begin{bmatrix}a_{ij} - b_{ij}\end{bmatrix}_{m\times n}$

Scalar multiplication
	Let s be a scalar and A = $\begin{bmatrix}a_{ij}\end{bmatrix}_{m\times n}$
		Then define $sA = \begin{bmatrix}sa_{ij}\end{bmatrix}_{m\times n}$ 

Product of two matrices
	Def A = $\begin{bmatrix}a_{ij}\end{bmatrix}_{m\times n}$ and B = *$\begin{bmatrix}b_{jk}\end{bmatrix}_{n\times p}$
		$AB = \begin{bmatrix}c_{ik}\end{bmatrix}_{m\times p}$
			Number of rows of first matrix and number of columns of the second matrix
			The columns of the first matrix must equal the number of rows in the second matrix
		$c_{ik} = c_{i1}b_{1k} + a_{i2}b{2k}+...+a_{in}b_{nk}$
		=$A(i, :)\cdot B(:,k)$
		$i$-$th$ row of A and $k$-$th$ column of B

 $A^2= A\cdot A$
	makes sense when A is a square matrix

Properties
Associativity $(AB)C = A(BC)$
Distributing $A(B+C) = AB+AC$
(Commutes with scalar multiplication) $s(AB) = (sA)B = A(sB)$

Caution, matrix multiplication is not necessarily commutative
	$AB \neq BA$ in general

$(A+B)^2 = A(A+B) + B(A+B)$
$A^2+AB+BA+B^2$


[[MATH 152 Lecture 17]]