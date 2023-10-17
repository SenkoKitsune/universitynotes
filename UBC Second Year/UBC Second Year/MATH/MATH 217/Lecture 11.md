A function on a closed interval $[a.b]$ achieves it's min/max at a critical point or at the boundaries

Classifying critical points of $f(x,y)$
	$(x_0,y_0)$ is a critical point of $f$ if $(\vec{\nabla}f)(x_0,y_0) = 0$
		The tangent plane at $(x_0,y_0)$ is horizontal
	Ordinary critical points come in 3 types
	
| Local Max            | Local Min             | Saddle point          |
| -------------------- | --------------------- | --------------------- |
| $z \approx -x^2-y^2$ | $z \approx x^2 + y^2$ | $z \approx y^2 - x^2$ |
|                      |                       |                       |
Global max/min occurs either at a critical point (local max or min) or the boundary of the domain
Once we find a critical point $(x_0,y_0)$, $(\vec{\nabla}F)(x_0,y_0) = 0$
	Use 2 variable 2<sup>nd</sup> derivative test
	$H = \begin{pmatrix}f_{xx} && f_{xy} \\ f_{yx} && f_{yy}\end{pmatrix}$
		$D = f_{xx}f_{yy}-f_{xy}^2$
		$D(x_0,y_0) < 0$, then $(x_0,y_0)$ is a saddle point
		$D(x_0,y_0) > 0$, then $(x_0,y_0)$ is a local min/max
			1) $D(x_0,y_0) < 0$ & $f_{xx} \text{ or } f_{yy} < 0$ is a local max
			2) $D(x_0,y_0) < 0$ & $f_{xx} \text{ or } f_{yy} > 0$ is a local min
		$D(x_0,y_0) = 0$ is not an ordinary critical point


1) If $D(x_0,y_0) > 0$, then if $\textrm{tr}(H) > 0$, then it is a local max
2) If $D(x_0,y_0) > 0$, the if $\textrm{tr}(H) < 0$, then it is a local min

