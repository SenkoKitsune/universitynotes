Find eigenvalues/eigenvectors
	
1) Eigenvalues are the roots of $\det(A-λI)$
2) Eigenvectors of eigenvalue λ are non-zero solutions of $(A-λI)\vec{x}=\vec{0}$

Complex eigenvalues/eigenvectors
$\displaystyle A = \begin{bmatrix}0 & -1 \\ 1 & 0\end{bmatrix}$
	rotation by $90^o$

To find eigenvalues, find roots of $\det(A-λI)$
	$\displaystyle \det(A-λI) = \det\begin{bmatrix}-λ& -1 \\ 1 & -λ\end{bmatrix}=λ^2+1$
	$λ^2+1 \to λ_1=i, λ_2=-i$

Find eigenvectors for $λ_1 = i$
	$\displaystyle \begin{bmatrix} A-iI & | & 0 \\ & | & 0\end{bmatrix} = \begin{bmatrix}-i&-1&|&0\\1&-i&|&0\end{bmatrix}$
	$\displaystyle \to \begin{bmatrix}1&-i&|&0\\0&0&|&0\end{bmatrix}$
	  $\displaystyle \begin{equation*}\left\{ \begin{aligned}x_1-ix_2=0 \\ x_2=t \end{aligned}\right.\end{equation*}$
	  $\to \begin{equation*}\left\{ \begin{aligned}x_1=i+t \\ x_2=t \end{aligned}\right.\end{equation*}\to \begin{bmatrix} x_1 \\ x_2\end{bmatrix} = t\begin{bmatrix}i\\1\end{bmatrix}$

In general, if A is a real $n\times n$ matrix, Then complex eigenvalues and eigenvectors appear in conjugate pairs

[[MATH 152 Lecture 30]]