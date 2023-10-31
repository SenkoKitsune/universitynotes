Vector calculus: calculus of vector valued functions

Vector valued function of several variables is known as vector fields
	$\vec{F}(x,y) = \left< P(x,y), Q(x,y) \right>$
	$= P(x,y)\vec{i} + Q(x,y)\vec{j}$

An example we have seen is the gradient vector field
	(if $f(x,y)$ is a scalar function, we get $\vec{\nabla}f = \left<f_x, f_y\right>$ is a vector field)
	A vector field $\vec{F}$ which is the gradient of $f$ is called conservative
		$\vec{F} = \vec{\nabla} f$
	$f(x,y)$ is called a potential function

Not every vector field is conservative

We also have vector fields in $\mathbb{R}^3$
	$\vec{F}(x,y,z) = \left<P(x,y,z),Q(x,y,z), R(x,y,z)\right>$
		$= P(x,y,z)\vec{i} + Q(x,y,z)\vec{j} + R(x,y,z)\vec{k}$
		Hard to draw, we often just draw the values at a surface

We will use the notation
	$\vec{r}(x,y) = \left<x,y\right>$
	$\vec{r}(x,y,z) = \left<x,y,z\right>$
	$r(x,y) = \left|\vec{r}(x,y)\right| = \sqrt{x^2+y^2}$
	$\hat{r}(x,y) = \dfrac{\vec{r}}{r} = \left<\dfrac{x}{\sqrt{x^2+y^2}}, \dfrac{y}{\sqrt{x^2+y^2}}\right>$
		$\dfrac{\vec{r}}{r}$ = unit vector field pointing away from origin

Example: $\vec{F}(x,y,z)$ be the gravitational force felt by a object of mass $m$ at $(x,y,z)$ if the sun with mass $M$ is at the origin
	$\vec{F} = -\hat{r}\cdot \dfrac{mMG}{r^2} = -\dfrac{mMG\cdot \vec{r}}{r^3}$
		$-\hat{r} \leftarrow$ pointed at the sun
		$r^2 \leftarrow$ inverse square law
		$G \leftarrow$ Gravitational constant
	$\vec{F} = \left<-\dfrac{mMG\cdot x}{\left(x^2+y^2+z^2\right)^{3/2}},-\dfrac{mMG\cdot y}{\left(x^2+y^2+z^2\right)^{3/2}}, -\dfrac{mMG\cdot z}{\left(x^2+y^2+z^2\right)^{3/2}} \right>$
	Let $f(x,y,z) = \dfrac{mMG}{r}$
		$= \dfrac{mMG}{\sqrt{x^2+y^2+z^2}}$
	$\displaystyle f_x  = -\dfrac{mMG\cdot x}{\left(x^2+y^2+z^2\right)^{3/2}}$
	$f_y = -\dfrac{mMG\cdot y}{\left(x^2+y^2+z^2\right)^{3/2}}$
	$f_z = -\dfrac{mMG\cdot z}{\left(x^2+y^2+z^2\right)^{3/2}}$
	$\left<f_x, f_y, f_z \right> = \vec{F}$

Suppose $\vec{r}(t) = \left< x(t), y(t), z(t) \right>$ is the path of a planet of mass m in the solar system
	$m \cdot a(t) = \vec{F}$