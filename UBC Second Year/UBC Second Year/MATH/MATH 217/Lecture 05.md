$\displaystyle \frac{dr}{dt} = \lim_{Δt} \frac{\vec{r}(t+Δt)-\vec{r}(t)}{ Δt}$
	$=<x\prime(t),y\prime(t),z\prime(t)>$

The product rules:
	$\displaystyle \frac{d}{dt}\left(f(t)\vec{r}(t) \right) = \frac{df}{dt}\vec{r}(t)+f\frac{dr}{dt}$
	$\displaystyle\frac{d}{dt}(\vec{u}\cdot \vec{v}) = \frac{d\vec{u}}{dt}\cdot\vec{v}+\vec{u}\cdot\frac{d\vec{v}}{dt}$
	$\displaystyle \frac{d}{dt}(\vec{u}\times\vec{v})=\frac{d\vec{u}}{dt}\times\vec{v}+\vec{u}\times\frac{d\vec{v}}{dt}$

Suppose $\vec{r}(t)$ has constant magnitude $|\vec{r}(t)| = C$
	$|\vec{r}(t)|^2 = \vec{r}(t)\cdot\vec{r}(t) = C^2$
		$\displaystyle\frac{d}{dt}(\vec{r}\cdot\vec{r})=\frac{d}{dt}(C^2)$
		$\vec{r}\prime\cdot\vec{r} + \vec{r}\cdot\vec{r}\prime = 0$
		$2\vec{r}\cdot\vec{r}\prime = 0$
		$\displaystyle \implies \vec{r}(t)\cdot\vec{r}\prime(t) = 0$
		$\implies \vec{r}(t)\perp \vec{r} \prime (t)$
			Sphere of radius C

 Arc length of a curve
	Arclength $\approx$ $\displaystyle \sum_{i=0}^{N-1}|\vec{r}(t_i+Δt) - \vec{r}(t_i)|$
	Arclength = $\displaystyle \lim_{N\to\infty}\sum_{i=0}^{N-1}\frac{|\vec{r}(t_i+Δt|-\vec{r}(t_i)|Δt}{Δt}$
		$\displaystyle\lim_{N\to\infty}\sum_{i=0}^{N-1}\left| \frac{d\vec{r}}{dt}(t_i) \right| Δt$
		$\displaystyle L =\int_{t=t_{start}}^{t_{end}}\left| \vec{r}\prime(t)\right|dt$
			We need $\vec{r}(t)$ to traverse the curve once (*no backtracking*)

$\vec{r}(t)$ = position
$\displaystyle\frac{d\vec{r}}{dt}$ = velocity
$\displaystyle \left|\frac{\vec{r}}{dt}\right|$ = speed
	Distance travelled is integral of speed

Linear equations in $\mathbb{R}^3 \to$ planes
Quadratic equations (involving $x^2, xy,y^2,z^2,x,y,z$) $\to$ 
	Quadratic equations in $\mathbb{R}^2$ ($x,y,x^2,y^2,xy$) $\to$ parabolas, ellipses, circles, hyperbolas
