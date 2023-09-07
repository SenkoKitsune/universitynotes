$\displaystyle A_{m\times n}\vec{v}_{n\times 1} = \vec{w}_{m\times 1}$

Linear transformation
$\displaystyle T: R^n \to R^m$ is linear if:
1) $\displaystyle T(\vec{v}+\vec{w}=T(\vec{v})+T(\vec{w})$
2) $T(s\vec{v}) = sT(\vec{V})$

Any matrix transformation is linear since 
1) $\displaystyle A(\vec{v}_1+\vec{v}_2=T(\vec{v}_1)+T(\vec{v}_2)$
2) $A(s\vec{v}) = sA(\vec{V})$

Ex) If T is a linear transformation: $R^n \to R^m$
	$T(\vec{0}_{R^n}) = \vec{0}_{R^m}$
	since $T(\vec{0}_{R^n}) = T(0\cdot\vec{0}_{R^n})$
	$=0\cdot T(\vec{0}_{R^n}) = \vec{0}_{R^m}$

Ex:

$\displaystyle A = \begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix} : R^2 \to R^2$
$\displaystyle \begin{bmatrix}x_1\\x_2\end{bmatrix} \to \begin{bmatrix}1&0\\0&1\end{bmatrix} \begin{bmatrix}x_1\\x_2\end{bmatrix} =  \begin{bmatrix}x_1+x_2\\x_2\end{bmatrix}$

Eg) counter-clockwise rotation by an angle θ
$\displaystyle Rot_θ(\vec{v}+\vec{w}) = Rot_θ(\vec{v})+Rot_θ(\vec{w})$

[[MATH 152 Lecture 19]]