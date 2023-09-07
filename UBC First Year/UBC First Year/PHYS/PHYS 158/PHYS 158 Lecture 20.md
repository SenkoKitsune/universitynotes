Current loop of radius $a$ carrying a current $I$ at $B(x=0)$
	$\displaystyle \vec{B} = \frac{μ_0I}{4πa^2}(2πa)$

B-field of a circular current ring $x > 0$
	$dB_x = dBcosθ$
	$\displaystyle dB_x = \frac{μ_0Idl}{4π(x^2+a^2)}\frac{a}{\sqrt{x^2+a^2}}$
	$\displaystyle B_x = \frac{μ_0}{4π}\frac{I(2πa)a}{(x^2+a^2)^{3/2}}=\frac{μ_0}{2}\frac{Ia^2}{(x^2+a^2)^{3/2}}$
		$\displaystyle x\to 0 \to B = \frac{μ_0}{2}\frac{Ia^2}{(a^2)^{3/2}} = \frac{μ_0}{2}\frac{Ia^2}{a^3}=\frac{μ_0I}{2a}$

Useful trig identity
$\sin(π-θ) = \sin(θ)$

Magnetic field of a short straight wire
	$\displaystyle \vec{B}_{at} {}_P = \int\vec{B} = \int\frac{μ_0}{4π} \frac{Id\vec{l}\times \hat{r}}{r^2}$
	$\displaystyle \vec{B}_{at} {}_P = \frac{μ_0I}{4π}\int_{-a}^{a}\frac{sin(θ)dy}{x^2+y^2}(-\hat{k})$
	$\displaystyle \vec{B}_{at} {}_P = \frac{μ_0I}{4π}\int_{-a}^{a}\frac{xdy}{(x^2+y^2)^{3/2}}(-\hat{k})$
	$\displaystyle \vec{B}_{at} {}_P = -\frac{μ_0I}{4π}\frac{2a}{x\sqrt{x^2+a^2}}\hat{k}$

Ampere's law
	enclosed path with an enclosed area
	$\displaystyle \oint \vec{B} \cdot d\vec{l} = μ_0i_{encl}$
		Requires symmetry to obtain B

Suppose we calculate $\displaystyle \sum\vec{B}\cdot d\vec{l}$ around a path shown for a simple case of an infinitely long straight line of current
	Using our previous result $\displaystyle B  = \frac{μ_0I}{2πr}$
		$\displaystyle \oint \vec{B}\cdot d\vec{l} = (2πr)\left(\frac{θ_0I}{2πr}\right)$

Ampere's Law is valid for any shape of path and any current distribution

[[PHYS 170 Lecture 21]]