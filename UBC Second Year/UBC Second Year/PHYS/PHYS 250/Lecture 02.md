$\beta = -$ corresponds to rest, increasing $\beta$ means faster
	$\beta \pm 1$ is the speed of light. It will turn out that $|u| \leq c$ so $|\beta| \leq 1$

$\gamma = 1$ corresponds to rest, increasing $\gamma$ means faster
	$\gamma$ is never less than 1. As $\beta$ approaches $\pm 1$, $\gamma$ goes to infinity

For small $\beta$, Taylor-expanding gives $\gamma \approx 1+\dfrac{1}{2}\beta^2$
Inverting, $\gamma^2 = \dfrac{1}{1-\beta^2} \to 1-\beta^2 = \dfrac{1}{\gamma^2} \to \beta = \sqrt{1-\dfrac{1}{\gamma^2}}$
Taylor expanding for large $\gamma$ gives $\beta \approx 1 - \dfrac{1}{2}\dfrac{1}{\gamma^2}$

Classical Doppler Effect
	For observer at rest and source moving away at velocity $u$,
		$\Delta T_{obs} = \Delta T_{source} + \dfrac{u\Delta T_{source}}{c} = \Delta T_{source}\left(1+\dfrac{u}{c}\right)$
		Since frequency $f=\dfrac{1}{\Delta T}$, $f_{obs} = \dfrac{f_{source}}{1+\dfrac{u}{c}}$
		Since wavelength $\lambda = c\Delta T, \lambda_{obs} = \lambda_{source}\left(1+\dfrac{u}{c}\right)$
	For source at rest, and observer moving away,
		$\Delta T_{obs} = \Delta T_{source} + \dfrac{u\Delta T_{source}}{c} = \Delta T_{source}\left(1-\dfrac{u}{c}\right)$
		$f_{obs} = \dfrac{f_{source}}{1-\dfrac{u}{c}}$

Extreme Classical Doppler Effect
	For an observer at rest, $f_{obs} = \dfrac{f_{source}}{1+\dfrac{u}{c}}$
	For a source at rest, $f_{obs} = f_{source}\left(1-\dfrac{u}{c}\right)$

Relativistic Doppler Effect
	For an observer at rest and source moving away, using observer's clock
		$\Delta T_{obs} = \gamma\Delta T_{source}\left(1+\dfrac{u}{c}\right) = \Delta T_{source}\dfrac{1+\dfrac{u}{c}}{\sqrt{\left(1+\dfrac{u}{c}\right)\left(1-\dfrac{u}{c}\right)}}$
		For wavelength, multiply both sides by $c$
			$\lambda_{obs} = \lambda_{source}\sqrt{\dfrac{1+\dfrac{u}{c}}{1-\dfrac{u}{c}}}$
		For frequency, take the reciprocal
	For a source at rest and observer moving away, we use the classical wave-front timing result, but the gamma factor goes with the moving observer
		$\gamma\Delta T_{obs} = \dfrac{\Delta T_{source}}{1-\dfrac{u}{c}}\implies \Delta T_{obs} = \Delta T_{source}\dfrac{\sqrt{1+\dfrac{u}{c}}}{\sqrt{1-\dfrac{u}{c}}}$
		For wavelength and reciprocal, it's the same as previous

4-Vector Notation

It's convenient to consider $ct$ at the 0th component of what is called _space-time coordinate 4-vector_ 
	<u>X</u> = $(ct, x,y, z) = (ct, \bar{x})$

Dot-product
	$\underline{X}_1 = (ct_1, \vec{x}_1)$
	$\underline{X}_2 = (ct_2, \vec{x}_2)$
	$\underline{X}_1 \cdot \underline{X}_2 = (ct_1)(ct_2) - \vec{x}_1 \cdot \vec{x_2}$
	It is invariant
		Remember that $\gamma^2 - \beta^2\gamma^2 = 1$
		So the 4-vector dot product of two coordinate 4-vectors is Lorentz invariant
			The same number in any reference frame if we transform both 4-vectors
		The square of the 4-vector is the 4-vector dot-product with itself


Momentum
	The denominator in the relativistic velocity addition formula is different for all the bodies in the collision which causes classical $p=mv$ momentum to not be conserved

It is best to think of many clocks in each frame. Each one shows the local time at nearby points. 
	If you look at a distant clock (in your frame) with a telescope, it will show an earlier time than a local clock, due to speed of light delay
We introduce another clock that moves along with the object we are defining
	The time measured by this clock is called proper time $\tau$
	If the velocity is moving with velocity $v$ in some frame, then proper time ticks by more slowly, with the relation $\gamma\tau = t$
	The normal velocity $v$ is defined as $v = \dfrac{dx}{dt}$
	The proper velocity $w$ is defined as $w = \dfrac{dx}{d\tau} = \dfrac{dx}{dt}\dfrac{dt}{d\tau} = v\cdot\dfrac{d}{d\tau}t = v\cdot \dfrac{d}{d\tau}\gamma\tau = v\gamma$

The relativistic momentum P is the regular mass $m$ times the proper velocity $w$
	$P = mw = \gamma mv = \dfrac{mv}{\sqrt{1-\dfrac{v^2}{c^2}}}$
The relativistic mass M is the regular mass $m$ times $\gamma$
	$M = \gamma m = \dfrac{m}{\sqrt{1-\dfrac{v^2}{c^2}}}$
	At low velocity, relativistic mass is the same as regular mass, but near light speed it's much larger
		