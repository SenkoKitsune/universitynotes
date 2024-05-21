$T_{//} = \dfrac{L}{c+u} + \dfrac{L}{c-u} = \dfrac{2L}{c}\dfrac{1}{1-\dfrac{u^2}{c^2}}$
So the effects get a $10^{-8}$ effect from 30km/s

To get the time in cycles
$cycles_{//} = \dfrac{c}{\lambda}\dfrac{2L}{c}\dfrac{1}{1-\dfrac{u^2}{c^2}} \approx \dfrac{2L}{\lambda}\left(1+\dfrac{u^2}{c^2}\right)$
There is also an effect on the other arm
$L'^2 = L^2 + \left(\dfrac{uT_{\perp}}{2}\right)^2$
	$T = \dfrac{2L'}{c}$

$cycles_{\perp} = T_{\perp}\cdot f \approx \dfrac{2L}{\lambda}\left(1+\dfrac{1}{2}\dfrac{u^2}{c^2}\right)$
The perpendicular arm extra delay has the same sign and is half as much, so the net effect is cut in half
	fringe shift = $cycles_{\parallel}-cycles_{\perp} \approx \dfrac{L}{\lambda}{u^2}{c^2}$
	
The Earth moves $2\pi \cdot 150\times10^6$ km around the Sun in $265.25\cdot 24\cdot 60\cdot 60 = 3.16\times 10^7$ sec, so $u = 29.86$ km/s
The Sun also orbits around the entre of mass of galaxy. This is estimated about 200km/s. 6.7 times faster than Earth vs Sun
Cosmic microwave background radiation looks a bit colder in one direction (more red-shift) than the opposite direction/ This implies our galaxy is moving about 630 km/s, 21 times faster than Earth vs Sun

A red-shift of 1.1 means the source is moving away at 10% the speed of light

Coordinate system Jargon
$S$ is a frame with origin $O$ for coordinate $x$ and time $t$
$S'$ is another frame with origin $O'$ for coordinate $x'$ and time $t'$
$S'$ is moving with velocity $u$ in the x-direction as seen from S

For arithmetical convenience, we assume that the origins of $O$ and $O'$ overlap at $t = t' = 0$ meaning $x = x' = 0$ at $t = t' = 0$

The Galilean Transformations:
	$x' = x - ut$            $t' = t$

To find velocity in $S'$, we take the time-derivative using $x'$ and $t'$
	$\dfrac{dx'}{dt'} = \dfrac{dx'}{dt} = \dfrac{d}{dt})(x-ut)=\dfrac{dx}{dt}-u$
		So velocities are different is $S'$: we subtract u
			That would make the speed of light frame-dependent, so these can't be the right coordinate transformations

Let's keep the x transform but try a time transformation that depends on position and velocity
	$x' = x-ut$
	$t' = t - \dfrac{ux}{c^2}$
	A light pulse is created in S at $t_1 = x_1 = 0$ and absorbed at $t_w = T, x_w = cT$
	Plug into transformation to find the $S'$ frame values:
		$x'_1 = 0, x_2' = (c-u)T$
		$t_1' = 0, t_2' = (1-\dfrac{u}{c})T$
	Find the velocity of light in $S'$ frame:
		$V' =\dfrac{x'_2-x'_1}{t'_2 - t'_1}= c$
	Additionally we would find the speed of light is the same in $S'$ and $S$ if we multiplied the transformation laws by any function of velocity $u$, as long as we use the same function for both
		$x' = (x-ut)\cdot f(u)$
		$t' = (t-\dfrac{ux}{c^2})\cdot f(u)$

The diagonal light path is $L' = \sqrt{L^2 + \left(\dfrac{uT'}{2}\right)}$, which depends on the period $T' = \dfrac{2L}{c} \to L' = \dfrac{T'}{2}$
Set these equal to get $T' = \dfrac{2L}{c}\dfrac{1}{\sqrt{1-\left(\dfrac{u}{c}\right)^2}}$
Time intervals are different by the factor $\dfrac{1}{\sqrt{1-\left(\dfrac{u}{c}\right)^2}}$
Set that to $f(u)$:
	$x' = (x-ut)\cdot \dfrac{1}{\sqrt{1-\left(\dfrac{u}{c}\right)^2}}$
	$t' = (t-\dfrac{ux}{c^2})\cdot \dfrac{1}{\sqrt{1-\left(\dfrac{u}{c}\right)^2}}$

When the light is moving in the same direction, the light pulse has to travel $cT_1 = L + uT_1$
Moving in the other direction, :$T_2 = \dfrac{L}{c+u}$

So the period is $T_1 + T_2 = \dfrac{2L}{c}\dfrac{1}{1-\dfrac{u^2}{c^2}}$

So moving objects appear shorter by a factor that makes the horizontal light clock tick at the same rate as the vertical clock

# Length of a moving object
We measure the coordinates in frame $S$ on both ends of a moving object at the same time $t = 0$ and $x_1 = 0, x_2 = L_{lab}$
	$x'_2 = \dfrac{x_2 - ut}{\sqrt{1-\left(\dfrac{u}{c}\right)^2}}$
The object length in its own frame is $L_{own} = x'_2 - x'_1 = \dfrac{L_{lab}}{\sqrt{1-\left(\dfrac{u}{c}\right)^2}}$
So $L_{lab} = L_{own}\sqrt{1-\left(\dfrac{u}{c}\right)^2} < L_{own}$

Lorentz Contraction
	$\beta \equiv \dfrac{u}{c}$      $\gamma \equiv \dfrac{1}{\sqrt{1-\beta^2}}$
	Moving objects look shorter: $L_{moving} = \dfrac{L_rest}{\gamma}$
	Time dilation: moving clocks tick slower: $T_{moving} = \gamma T_{rest} \leftrightarrow f_{moving} = \dfrac{f_{rest}}{\gamma}$

Simplify the transform notation
	We can write $x' = \gamma \cdot (x - \beta ct)$ and $t' = \gamma \cdot \left(t - \dfrac{\beta cx}{c^2}\right)$
	Then cancel the time rule and multiply both sides by c: $ct' = \gamma\cdot (ct - \beta x)$

So the rules can be written as
	$x' = \gamma\cdot (x - \beta ct)$
	$ct' = \gamma\cdot (ct - \beta x)$

We want $\dfrac{\Delta s}{\Delta t} = \dfrac{\sqrt{(x'_2 - x'_1)^2 + (y_2'-y_1')^2}}{t'_2 - t_1'} = c$
Simply and solve for $y_2'$
	$(y_2')^2 = (\gamma^2 - \beta^2\gamma^2)(cT^2)$
	So $(y_2')^2 = 1\cdot(cT)^2 = (y_2)^2$
		The y-coordinate doesn't change

# Relativistic Velocity Addition
If an object is moving with velocity $v'$ as measured in $S'$ which is moving with velocity $u$ seen from the $S$ frame
	$x = x' = 0$ and $t = t' = 0$
		In the $S'$ frame, at time $t'$ it will be at $x' = v't'$
		In the S frame, that corresponds to
			$x = \gamma (v' + u)t'$
			$ct = \gamma\left(1+\dfrac{uv'}{c^2}\right)ct'$
			The velocity in the S frame is
				$v = \dfrac{x}{t} = \dfrac{x}{ct\dfrac{1}{c}} = \dfrac{v'+u}{1+\dfrac{v'\cdot u}{c^2}}$
			The denominator keeps the velocity as less than $c$
			Something moving at $c$ in $S'$ is also moving at $c$ in $S$, independent of $u$
Define $\beta' = \dfrac{v'}{c}$ and $\beta = \dfrac{u}{c}$ to write $\dfrac{v}{c}$ as $\dfrac{\beta' + \beta}{\beta\cdot\beta' + 1}$
