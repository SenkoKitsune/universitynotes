Rewrite the linear approximation equation
	$\displaystyle z\approx z_0 + f_x(x_0,y_0)\Delta x + f_y(x_0,y_0)\Delta y$
	$\displaystyle\Delta z \approx \frac{\partial f}{\partial x}\Delta x + \frac{\partial f}{\partial y}\Delta y \to \text{limit } \Delta x, \delta y \to \infty$
		$\displaystyle dz = \frac{\partial f}{\partial x}dx + \frac{\partial f}{\partial dy}$  

Chain rule:
	$y = f(g(t))$
	$\displaystyle \frac{dy}{dt} = f\prime(g(t))g\prime(t)$
		$x = g(t), y = f(x)$
		$\displaystyle \frac{dy}{dt}=\frac{dy}{dx}\frac{dx}{dt}$
	$z = f(g(t),h(t))$
		$z = f(x,y), x = g(t), y = h(t)$
		$\displaystyle \frac{dz}{dt} = \frac{\partial z}{\partial x}\frac{dx}{dt} + \frac{\partial z}{\partial y}\frac{dy}{dt}$

If $z = f(x,y), x = g(s,t), y = h(s,t)$
	$\displaystyle\frac{\partial z}{\partial s} = \frac{\partial z}{\partial x}\frac{\partial x}{\partial s}+\frac{\partial z}{\partial y}\frac{\partial y}{\partial s}$
		$\displaystyle\frac{\partial z}{\partial t} = \frac{\partial z}{\partial y}\frac{\partial y}{\partial t}+\frac{\partial z}{\partial y}\frac{\partial y}{\partial t}$
		$\displaystyle\begin{pmatrix} \displaystyle \frac{\partial z}{\partial s} \\ \displaystyle \frac{\partial z}{\partial t}\end{pmatrix} = \begin{pmatrix} \displaystyle \frac{\partial x}{\partial s} && \displaystyle \frac{\partial y}{\partial s} \\ \displaystyle \frac{\partial x}{\partial t} && \displaystyle \frac{\partial y}{\partial t}\end{pmatrix}\begin{pmatrix} \displaystyle \frac{\partial z}{\partial x} \\ \displaystyle \frac{\partial z}{\partial y}\end{pmatrix}$ 

$z = f(x,y), x = r\cos(\theta), y = r\sin(\theta)$
	$\begin{pmatrix} \displaystyle \frac{\partial x}{\partial r} && \displaystyle \frac{\partial y}{\partial r} \\ \displaystyle \frac{\partial x}{\partial \theta} && \displaystyle \frac{\partial y}{\partial \theta}\end{pmatrix} = \begin{pmatrix} \cos(\theta) && \sin(\theta) \\ -r\sin(\theta) && r\cos(\theta) \end{pmatrix} \to \text{determinant = } r$

