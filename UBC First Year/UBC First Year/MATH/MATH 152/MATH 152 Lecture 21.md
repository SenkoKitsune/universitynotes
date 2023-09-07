Applications
Population model

eg) city + suburb
	$C_K$ = city population in year K
	$S_K$ = suburb population in year K
Model:
	initial condition/population $\begin{bmatrix}C_0 \\ S_0 \end{bmatrix} = \begin{bmatrix}3\\2\end{bmatrix}$
	Change per year
		80% from city to city
		20% from city to suburbs
		10% from suburbs to city
		90% from suburb to suburbs
	Example of questions
		1) What is the population in the city in year 2
		2) What is the population distribution in year $\infty$

1) What is the population in the city in year 2
	Write down the model in terms of matrix
	$\begin{equation*}\left\{ \begin{aligned} C_{K+1} = 0.8C_K + 0.1S_K  \\ S_{K+1} = 0.2C_K+0.9S_K \end{aligned}\right.\end{equation*}$
	$\begin{bmatrix}C_{K+1} \\ S_{K+1} \end{bmatrix} = \begin{bmatrix}0.8 & 0.1 \\ 0.2 & 0.9\end{bmatrix}\begin{bmatrix}C_K \\ S_K\end{bmatrix}$
		$\begin{bmatrix}0.8 & 0.1 \\ 0.2 & 0.9\end{bmatrix}$ = transition matrix A
		$\begin{bmatrix}C_K \\ S_K\end{bmatrix} = \vec{P}_K$
		
$\vec{P}_K+1 = A\vec{P}_K = A(A\vec{P}_0) = A^2\vec{P}_0$

$\vec{P}_2 = A\vec{P}_1$
$= \begin{bmatrix}0.8 & 0.1 \\ 0.2 & 0.9 \end{bmatrix}\begin{bmatrix}0.8 & 0.1 \\ 0.2 & 0.9 \end{bmatrix}\begin{bmatrix}3 \\ 2 \end{bmatrix}$
$=\begin{bmatrix}0.66 & 0.17 \\ 0.34 & 0.83 \end{bmatrix}\begin{bmatrix}3\\2\end{bmatrix} = \begin{bmatrix} 2.32 \\ 2.68\end{bmatrix}$
In general,
	$\vec{P}_K = A\vec{P}_{K-1} = A(A\vec{P}_{K-2}) = A\cdot A\cdot A \cdot ... \cdot A\vec{P}_0$
		$= A^K\vec{P}_0$

2) Does the limit $\vec{P}_\infty$ exist?
	$\begin{equation*}\left\{ \begin{aligned} \vec{P}_\infty = A\vec{P}_\infty \\ x_1 + x_1 = 5 \end{aligned}\right.\end{equation*}$
	$\vec{P}_\infty = \begin{bmatrix}x_1 \\ x_2\end{bmatrix}$
	Total population is constant

$\begin{equation*}\left\{ \begin{aligned} \begin{bmatrix}x_1 \\ x_2\end{bmatrix} = A\begin{bmatrix}x_1 \\ x_2\end{bmatrix} \\ x_1 + x_2 = 5 \end{aligned}\right.\end{equation*}$

$= \begin{equation*}\left\{ \begin{aligned}(A-I)\begin{bmatrix} x_1 \\ x_2\end{bmatrix} = \begin{bmatrix}0 \\ 0 \end{bmatrix} \\ x_1 + x_2 = 5 \end{aligned}\right.\end{equation*}$

$= \begin{equation*}\left\{\begin{aligned}\begin{bmatrix}-0.2 & 0.1 \\ 0.2 & -0.1\end{bmatrix}\begin{bmatrix} x_1 \\ x_2\end{bmatrix} = \begin{bmatrix}0 \\ 0 \end{bmatrix} \\ x_1 + x_2 = 5 \end{aligned}\right.\end{equation*}$

Random walk
1) A person lives in the city C in year 0. What is the probability of the person living in the city suburb in year K
	$C_K$ = probability of this person living in the city in year K
	$S_K$ = probability of this person living in the suburbs in year K
	$\vec{P}_K = \begin{bmatrix}C_K \\ S_K\end{bmatrix}$

Probability vector
	dim = # of possible events
	$C_K + S_K = 1$
	The columns of the matrix are probability vectors

[[MATH 152 Lecture 21]]