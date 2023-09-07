Finding λ and $\vec{v}$ $\to$ related to $\to$ solving linear systems
$\displaystyle A\vec{v} = λ\vec{v} \leftrightarrow (A-λI)\vec{v} = \vec{0}$
	$\displaystyle (A-λI)\vec{x} = \vec{0}$ has a non-zero solution $\vec{v}$
	$\det(A-λI) = 0$ since RREF$(A-λI)$ has a row of zeros

Eigenvalues are those that make 
	$\det(A-λI)=0$

Eigenvectors whose eigenvalues is λ are the non-zero solutions of
	$(A-λI)\vec{x} = \vec{0}$

Eg) Find the eigenvalue/eigenvector for $\displaystyle A = \begin{bmatrix}2 & 3\\1 & 0\end{bmatrix}$
	$\displaystyle \det(A-λI)=\det\left(\begin{bmatrix}2&3\\1&0\end{bmatrix}-λ\begin{bmatrix}1&0\\0&1\end{bmatrix}\right)$
	$\displaystyle =\det\left(\begin{bmatrix}2-λ&3\\1&-λ\end{bmatrix}\right)=(2-λ)(-λ)-1\cdot 3$
	$= λ^2-2λ-3$
	Roots and eigenvalues:
		$λ = 3, λ = -1$
This is a polynomial in λ, and is called the **characteristic polynomial of A**

$λ=3$ Find $\vec{v}\neq 0$ so that $(A-3I)\vec{v} = \vec{0}$
	Solve $(A-3I)\vec{x}=\vec{0}$
	$\displaystyle \begin{bmatrix}-1&3 & | & 0 \\ 1 & -3 & | & 0\end{bmatrix}\to \begin{bmatrix}-1 & 3 & | & 0\\ 0&0&|&0\end{bmatrix}$
		$\displaystyle \to \begin{equation*}\left\{ \begin{aligned}x_1-3x_2=0 \\ x_2=t \end{aligned}\right.\end{equation*}, t\in\mathbb{R}$

$λ=-1$
	$\displaystyle \begin{bmatrix}3&3&|&0\\1&1&|&1\end{bmatrix} \to \begin{bmatrix} 1 & 1 &|&0\\0&0&|&0\end{bmatrix}$
		$\displaystyle \begin{bmatrix}x_1\\x_2\end{bmatrix}=t\begin{bmatrix}1\\-1\end{bmatrix}$
			$t\neq 0$ is an eigenvector

In the example above, $\mathbb{R}^2$ has a basis consisting of eigenvectors
	$\displaystyle \left\{\begin{bmatrix}3\\1\end{bmatrix},\begin{bmatrix}1\\-1\end{bmatrix}\right\}$
	Such a basis is called an eigen basis
A basis for $\mathbb{R}^n$ is a set consisting of $n$ linearly independent vectors in $\displaystyle \mathbb{R}^n$
There are some matrices that do not have an eigen basis

[[MATH 152 Lecture 29]]