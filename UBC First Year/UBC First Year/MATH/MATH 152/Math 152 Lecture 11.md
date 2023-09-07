None unique/ infinitely many solutions

pivot variables are non-free variables
solve pivot variables in terms of free variables


If there is a free variable and the augmentation column doesn't have a pivot, then there are infinitely many solutions

Ex) $\begin{equation*}\left\{ \begin{aligned}x + cy = -1 \\ cx + 4y = 2 \end{aligned}\right.\end{equation*}$
For what C does the system have 1) no solution, 2) infinite solutions, 3) unique solution

$\displaystyle\begin{bmatrix} 1 && C && -1 \\ C && 4 && 2\end{bmatrix}$ -> $R_2 - CR_1$ -> $\displaystyle\begin{bmatrix} 1 && C && -1 \\ 0 && 4-C^2 && 2+C\end{bmatrix}$

1) No solution
$\displaystyle\begin{bmatrix}1 && C && -1 \\ 0 && 0 && non-zero\end{bmatrix}$

$\begin{equation*}\left\{ \begin{aligned}4-C^2 = 0\\ 2+C \neq 0 \end{aligned}\right.\end{equation*}$

C = 2


2) Infinite solutions
Need $\displaystyle\begin{bmatrix}1 && C && -1 \\ 0 && 0 && 0\end{bmatrix}$
	
$\begin{equation*}\left\{ \begin{aligned}4-C^2 = 0\\ 2+C = 0 \end{aligned}\right.\end{equation*}$

C = -2

3) Unique solution
Need $\displaystyle\begin{bmatrix}1 && C && -1 \\ 0 && non-zero && any constant\end{bmatrix}$

$\begin{equation*}\left\{ \begin{aligned}4-C^2 \neq 0\\ C \neq ±2 \end{aligned}\right.\end{equation*}$

If a system has at least one solution, it is called *consistent*, otherwise, it is called inconsistent

Let **A** be a matrix (not necessarily an augmentation matrix)
	The rank of A is equal to the number of pivots in the echelon form of A

[[MATH 152 Lecture 12]]