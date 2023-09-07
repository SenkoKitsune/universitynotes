Linear transformations are matrix transformations

Composition of transformations
	$T_1 = R^n \to R^m$
	$T_2 = R^m \to R^l$
	$T_2 \circ T_1: R^n \to R^l$
		$\vec{v} \to T_2(T_1(\vec{v}))$

Suppose $T_1$ and $T_2$ are linear transformations,
	$T_1(\vec{v}) = B_{m\times n}\vec{v}$
	$T_2(\vec{w}) = A_{l\times m}\vec{w}$
	$T_2\circ T_1$ is still a linear transformation

$(T_2\circ T_1)(\vec{v}) = T_2(T_1(\vec{v})) = T_2(B_{m\times n}\vec{v})=A_{l\times m}(B_{m\times n}\vec{v})$
	$= (AB)\vec{v}$

Matrix for $T_2\circ T_1$ is equal to $AB$
	$T_2$ ~ A, $T_1$ ~ B

$Rot_θ: R^2 \to R^2 = \begin{bmatrix}cosθ & -sinθ \\ sinθ & cosθ\end{bmatrix}$

$Ref_L: R^2 \to R^2$:
	Let L = y-axis: $\begin{bmatrix} | & | \\ Ref_L(\vec{e_2}) & Ref_L(\vec{e_2}) \\ | & |\end{bmatrix}$
	$Ref_L(\vec{e_1}) = \begin{bmatrix}-1 \\ 1\end{bmatrix}$
	$Ref_L(\vec{e_2}) = \begin{bmatrix}0\\1\end{bmatrix}$
	$Ref_L = \begin{bmatrix}-1 & 0 \\ 0 & -1\end{bmatrix}$

Ex) $T = Ref_{y-axis}\circ Rot_{π/2}$
1) Figure out $T(\vec{e_1})$ & $T(\vec{e_2})$
	$\begin{equation*}\left\{ \begin{aligned}T(\vec{e_1} = Ref_{y-axis}\circ Rot_{π/2}(\vec{e_1} = \vec{e_2} \\  T(\vec{e_2}) = Ref_{y-axis}\circ Rot_{π/2}(\vec{e_2}) = \vec{e_1} \end{aligned}\right.\end{equation*}$

2) $Rot_{π/2}$ ~ $\begin{bmatrix}0 & -1 \\ 1 & 0\end{bmatrix}$
	$= \begin{bmatrix}-1 & 0 \\ 0 & 1\end{bmatrix}\begin{bmatrix}0 & -1 \\ 1 & 0\end{bmatrix}$
	$= \begin{bmatrix}-0 & 1 \\ 1 & 0\end{bmatrix}$

Ex. $\displaystyle Rot_θ\circ Rot_Φ = Rot_{θ+Φ}$
$\begin{bmatrix}cos(θ) & -sin(θ) \\ sin(θ) & cos(θ)\end{bmatrix}\begin{bmatrix}cos(Φ) & -sin(Φ) \\ sin(Φ) & cos(Φ)\end{bmatrix}=\begin{bmatrix}cos(θ+Φ) & -sin(θ+Φ) \\ sin(θ+Φ) & cos(θ+Φ)\end{bmatrix}$
	Use trig identities to get to final answer after cross product

[[MATH 152 Lecture 21]]