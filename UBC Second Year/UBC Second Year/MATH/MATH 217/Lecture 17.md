$\displaystyle \vec{\nabla} = \vec{i}\frac{\partial}{\partial x} + \vec{j}\frac{\partial}{\partial y} + \vec{k}\frac{\partial}{\partial z}$
	Formal combination of vector and differential operators

$\textrm{curl}\vec{F} = \vec{\nabla}\times\vec{F}$
	$\vec{F} = \left<P,Q,R\right>$
	$\displaystyle \vec{\nabla} = \left<\frac{\partial}{\partial x},\frac{\partial}{\partial y},\frac{\partial}{\partial z}\right>$
	$\vec{\nabla} \times \vec{F} = \det\begin{bmatrix} \vec{i} && \vec{j} && \vec{k} \\ \dfrac{\partial}{\partial x} && \dfrac{\partial}{\partial y} && \dfrac{\partial}{\partial z} \\ P && Q && R \end{bmatrix}$
		$= (R_y - Q_z)\vec{i} + (P_z - R_x)\vec{j} + (Q_x - P_y)\vec{k}$
	Note if $\vec{F} = \vec{\nabla}f$, then $P = f_x$, $Q = f_y$, $R = f_z$
	$R_y - Q_z = f_{zy} - f_{yz} = 0$
	$P_z - R_x = f_{xz} - f_{zx} = 0$
	$Q_x - P_y = f_{yx} - f_{xy} = 0$
		$\vec{\nabla} f = \left(\vec{i}\frac{\partial}{\partial x} + \vec{j}\frac{\partial}{\partial y} + \vec{k}\frac{\partial}{\partial z}\right) f$
			$= f_x\vec{i} + f_y\vec{j} + f_z\vec{k}$

$\textrm{curl}\left(\textrm{grad }f \right) = 0$
or $\vec{\nabla} \times \left(\vec{\nabla} f \right) = \vec{0}$
	Necessary condition for $\vec{F}$ to be conservative is $\vec{\nabla} \times \vec{F} = \vec{0}$
		This condition is sufficient if the domain of $\vec{F}$ is <u>simply connected</u>

We want to integrate functions and vector fields along curves
	Called line integrals



