Constant acceleration
	We now consider the important special case where acceleration, a, is constant, $a_c$

$\displaystyle a_c = \frac{dv}{dt}$, 
$\displaystyle \int_{v_0}^{v}dv=\int_{0}{t}a_cdt$
$\displaystyle v - v_0 = a_ct$

Position as a function of time
$\displaystyle v = frac{ds}{dt}$
$\displaystyle \int_{s_0}^{s}ds = \int_{0}{t}vdt = \int_{0}^{t}(v_0+a_ct)dt$
$s-s_0 = v_0t+ \displaystyle\frac{1}{2}a_ct$
velocity as a function of position

$vdv = ads$
$\displaystyle\int_{v_0}^{v}vdv = \int_{s_0}^{s}a_cds$

$\displaystyle\frac{v^2}{2}-\frac{v_0^2}{2} = ac(s-s_0)$

Position
	Particle moves along path defined (parameterized) by path function, s
	Relative to the point O (typically origin of coordinate system)
	Location of particle is given by the position vector, $\vec{r}$
Displacement
	Change in position of particle over some time interval, Δt, during which the particle traverses a distance Δs along the path
	$Δ\vec{r} = \vec{r'} - \vec{r}$
	$Δ\vec{r}$ can be viewed as a straight line displacement
Velocity
	Average velocity 
		over time interval, Δt, the average velocity
			$\displaystyle \vec{v}_{avg}=\frac{Δ\vec{r}}{Δt}$
	Instantaneous velocity
	$\displaystyle\vec{v} = \lim_{Δt\to 0}\frac{Δ\vec{r}}{Δt}$	
	$\displaystyle v = \frac{dx}{dt}$

Acceleration
	Average acceleration
		$\displaystyle \vec{a}_{avg} = \frac{Δ\vec{v}}{Δt}$
		We can study this time rate of change by translating the velocity vectors so that their tails coincide at some fixed point
		Velocity arrowheads then touch points on a curve known as a hodograph
	Instantaneous acceleration
		$\displaystyle \vec{a}=\lim_{Δt\to 0}\frac{\vec{v}}{t}$
		$\displaystyle\vec{a} = \frac{d\vec{v}}{dt}$
		$\displaystyle \vec{a} = \frac{d^2\vec{r}}{dt^2}$

Curvilinear motion: rectangular components

Position
	Assume at some instant, t, that the particle is at point $P = P(x,y,z)$ along the path
	The particle position is then defined by the position vector $\vec{r}$
		$\displaystyle \vec{r} = x\hat{i} + y\hat{j} + z\hat{k}$
	The magnitude, r, of the position vector is given by
		$\displaystyle r = \sqrt{x^2+y^2+z^2}$

Velocity
	$\displaystyle \vec{v} = \frac{dx}{dt} = \frac{d}{dt}(xi) + \frac{d}{dt}(yj) + \frac{d}{dt}(zk)$
	$\displaystyle \frac{d}{dt}(xi) = \frac{dx}{dt} i = \dot{x}i = v_xi$
	Magnitude
		$v = \sqrt{v_x^2+v_y^2+v_z^2}$

Acceleration
	$\displaystyle\vec{a} = \frac{d\vec{v}}{dt} = a_x\hat{i}+a_y\hat{j}+a_z\hat{k}$
	$\displaystyle\vec{a}_x=\dot{\vec{v}_x} = \ddot{x} = \frac{d^2x}{dt^2} = \frac{d\vec{v}_x}{dt}$
	Direction of acceleration
		given by components of unit vector
			$\displaystyle\vec{u}_a = \frac{\vec{a}}{a}$

Projectile Motion
	Particle motion is determined by initial conditions
		Initial position 
			$\displaystyle\vec{r} = x_0\hat{i} + y_o\hat{j}$
		Initial velocity
			$\displaystyle\vec{v} = (v_0)_x\hat{i} + (v_0)_y\hat{j}$

Trajectory equation
	$\displaystyle x = x_0 + v_0cos(θ_0)t$
	$\displaystyle y = y_0+v_0sin(θ_0)t - \frac{1}{2}gt^2$
	$\displaystyle t = \frac{x-x_0}{v_0cos(θ_0)}$
	$\displaystyle y(x) = a(x-x_0)^2 + b(x-x_0) + y_0$
	$\displaystyle a = -\frac{g}{2v_0^2cos^2(θ_0)}$
	$b = tan(θ_0)$

[[PHYS 170 Lecture 21]]