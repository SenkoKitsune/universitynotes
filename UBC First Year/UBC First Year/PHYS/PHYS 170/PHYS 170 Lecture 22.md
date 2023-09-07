Curvilinear Motion: Cylindrical and polar coordinates

2D (planar motion): Polar coordinates: $(r, θ)$

Consider particle located at position, $P$, and traveling along some path

We locate the particle by specifying
1) Radial coordinate, $r$, measured outwards from the origin, $O$, of the polar coordinate system
2) Transverse or angular coordinate, $θ$, measured counter clockwise from a fixed axis through the origin (typically a horizontal axis); direction of $θ$ is perpendicular to the $r$-axis
	1) Natural units of the angular coordinate are radians

Rad/s = $\dot{θ}$
Rad/s<sup>2</sup> = $\ddot{θ}$

With each of the $r, θ$ axes, we can associate unit vector $u_r$ and $u_θ$, which are perpendicular to one another
(Positive) direction of $u_r$: Hold θ fixed; $u_r$ points in direction of increasing $r$

Positive direction of $u_θ$, Hold $r$ constant.

$\vec{v}_r = \dot{r}\vec{u}_r$: radial component
	time rate of change of radial position
$\vec{v}_θ = (r\dot{θ})\vec{u}_θ$
	transverse component
$\dot{θ} = \displaystyle\frac{dθ}{dt}$ is known as the angular velocity

Magnitude of velocity
	$\displaystyle v = \sqrt{v^2_r + v^2_θ} = \sqrt{\dot{r}^2+(r\dot{θ})^2}$


To determine $\vec{v}$ and $\vec{a}$ in polar coordinates, we need 4 time derivatives
	$\dot{θ}, \ddot{θ}, \dot{r}, \ddot{r}$
Two types of questions
1) Particle path is given in the form $r = r(t)$ and $θ = θ(t)$
	We can calculate the derivatives directly
2) Particle path is given in the form $r = f(θ)$
	We need to use the chain rule to computes the relationship between the radial and angular (transverse) derivatives

Position 
$\vec{r} = r\vec{u}_r$

Velocity
$vec{v} = v_r\vec{u}_r + v_θ\vec{u}_θ$
	$v_r = \dot{r}$
	$v_θ = dot{θ}$

Acceleration
$\vec{a} = a_r\vec{u}_r + a_θ\vec{u}_θ$
	$a_r = \ddot{r} - r\dot{θ}^2$
	$a_θ = r\ddot{θ} + 2\dot{r}\dot{θ}$

[[PHYS 170 Lecture 23]]