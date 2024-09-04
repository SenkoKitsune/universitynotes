Definition: A system of linear equations is a collection of equations of the form
	m equations $\begin{equation*}\left\{ \begin{aligned} a_{11}X_1 + a_{12}X_2 + \dots + a_{1n}X_n = b_1 \\ a_{21}X_1 + a_{22}X_2 + \dots + a_{2n}X_n  = b_2\\ \dots \\ a_{m1}X_1 + a_{m2}X_2 + \dots + a_{mn}X_n = b_n  \end{aligned}\right.\end{equation*}$
	Where $a_{ij}$ and $b_i$ are known variables
	X's are unknowns

In Matrix form:
	$A\underline{x} = b$
	$A = \begin{bmatrix} a_{11} && a_{12} && \dots && a_{1n} \\ a_{21} && a_{22} && \dots && a_{2n} \\ \vdots \\ a_{m1} && a_{m2} && \dots && a_{mn}\end{bmatrix}$ is the coefficient matrix
	$\underline{X} = \begin{bmatrix} x_1 \\ x_2 \\  \vdots \\ x_n \end{bmatrix}$ is the vector of variables
	 and $\underline{b} = \begin{bmatrix} b_1 \\ b_2 \\  \vdots \\ b_n \end{bmatrix}$ is the coefficient vector
The augmented matrix of the system $A\underline{x} = \underline{b}$ is 
	$\left[A | b \right] = \begin{bmatrix} a_{11} && \dots && a_{1n} && | && b_1 \\ \vdots && && \vdots \\ a_{m1} \dots a_{mn$
	