$I_{peak} = \displaystyle\frac{V_{peak}}{Z_r}$ across resistors

$\displaystyle I_{peak} = \frac{V_{peak}}{Z_T}$ across inductor

Kirchhoff's voltage law always applies
	The addition of instantaneous voltages involves both the amplitude and the phase of the instantaneous voltages
Resonance in AC circuits
	Imagine the frequency ω of the voltage source $V_s$ is changed smoothly
	The current $I(ω)$ varies as
		$\displaystyle I = \frac{V_{source}}{Z_T}=\frac{V_{source}}{\sqrt{R^2+(ωL + \frac{1}{ωC})^2}}$
		The current at both limits is zero
			suggests it may have a maximum somewhere in between
		When $X_L = X_C$, the current is at its maximum
			$\displaystyle I = \frac{V_{source}}{R}$
		And the  frequency at which resonance occurs is 
			$\displaystyle ω_0 = \frac{1}{\sqrt(LC)}$
The lower a circuit's resistance, the higher and sharper is the resonance peak near the resonance angular frequency $ω_0$

Application of AC circuits
	Electronic filters

Power dissipation in the inductor is
	$P_L(t) = i(t)V_L(t)$

Power dissipation in AC circuits
	Power dissipation in a resistor
	$P_R(t)=i(t)V_R(t)$, or $P=i(t)^2R$, or $\displaystyle P(t)=\frac{V_R(t)^2}{R}$
The phase angle Φ between current I and voltage V applied to a series RLC circuit can vary from $-90^o$ to $+90^o$
	$v(t)=V_{peak}cos(ωt+Φ)$
	$i(t) = I_{peak}cos(ωt)$
Average dissipated power
	$\displaystyle P_{av} = <P(t)> = \frac{1}{T}\int_{0}^{T}P(t)dt$
	$\displaystyle P_{av}=I_{peak}V_{peak}[<(cos^2(ωt))cosΦ-(cos(ωt)sin(ωt))sinΦ]$
	Using $cos^2(ωt) = \displaystyle\frac{1}{2}$ and $(cos(ωt)sin(ωt)) = 0$
	$\displaystyle P_{av} = \frac{1}{2}I_{peak}V_{peak}cosΦ$
We can write $P_{av} = I_{rms}I_{rms}ZcpsΦ$
	but $cos(Φ)=\displaystyle\frac{R}{Z}$
	We also find that
	$\displaystyle P_{av} = I^2_{RMS}R$

[[PHYS 158 Lecture 12]]