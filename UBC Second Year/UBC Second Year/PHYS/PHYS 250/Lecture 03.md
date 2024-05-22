Electromagnetic waves can only have certain discrete (quantized) amplitudes
	Photons have energy $E=hf$, where $h$ is Planck's constant and $f$ is the frequency
	Momentum, satisfying $E = pc$, so $p = \dfrac{E}{f} = \dfrac{hf}{c}$
	Photon scattering from charged particles changes the momentum of both

The probability for a small sub-system to have energy E is proportional to $e^{\dfrac{E}{kT}}$

In a conducting metal box, there can be oscillating electromagnetic fields
	There are boundary conditions: electric field parallel to a metal surface must be zero, magnetic field normal to a metal surface must be zero
If the box is rectangular, the allowed frequencies are 
	$f = \dfrac{c}{2}\sqrt{\dfrac{n_x^2}{a_x^2}+\dfrac{n_y^2}{a_y^2} + \dfrac{n_z^2}{a_z^2}}$
	where $a_x, a_y, a_z$ are the dimensions of the box, and $n_x, n_y, n_z$ are the number of half-cycles across each dimension, integers 1,2,3, etc.

Rayleigh-Jeans predication
	The EM modes form a grid in $n_x, n_y$, and $n_z$ space, up to infinite $n$ values
	The number of allowed frequencies less than $f$ is proportional to $f^3$, so the number near $f$ is proportional to $f^2df$
		$dI_{RJ}(f) = \dfrac{2f^2}{c^2}kTdf$
		This is the power flow in $\dfrac{J}{s\cdot m^2}$ that would come out of a small hole cut in a metal box at temperature $T$
	Using $f = \dfrac{c}{\lambda}$ so $df = \dfrac{c}{\lambda^2}d\lambda$ and $f^2df = \dfrac{c^2}{\lambda^2}\dfrac{c}{\lambda^2}df$
	$dI_{RJ}(\lambda) = \dfrac{2c}{\lambda^4}kTd\lambda$
		Does not work for black body radiation: predicts that thermal radiation should be much larger than seen and go to infinity at short wavelength

Wein Spectrum:
	$dI_w(f) = Af^3e^{-\frac{Bf}{T}}df$
	The radiated power between $f$ and $f+df$ is $dI_w(f)$
	This can also be written using wavelength
		$dI_w(f) = A\dfrac{c^4}{\lambda^5}e^{-\frac{Bc}{\lambda T}}d\lambda$
Planck Spectrum
	$dI_p(f) = \dfrac{Af^3}{e^{\frac{Bf}{T}}- 1}df = \dfrac{Af^3}{e^{\frac{hf}{k_BT}}- 1}df$	
	At low frequency, $e^{\frac{Bf}{T}}- 1 \to \dfrac{Bf}{T}$ so we get Rayleigh-Jeans\
	At high frequency, we get Wein

In statistical mechanics, continuous variables have average energy $\dfrac{kT}{2}$ but discrete variables are controlled by the Boltzmann factor $e^{-\dfrac{\Delta E}{kT}}$


Planck's constant:
	$h = 6.626\times 10^{-34}$ Joule-seconds
	$h = 4.136 \times 10^{-15}$ eV-s
	Using wavelength instead of frequency:
		$hc 1.24 \times 10^{-6}$ eV-m $= 1.240$ eV-$\mu$m $= 1240$ eV-nm

Planck's model says EM waves can only have amplitudes that make their energy $E = nhf$
Energy depends not only on wave amplitude, but also on dimensions of the box
	But that means the wave knows the dimensions of the box

Photoelectric effect
	Shinning light on a metal surface (photocathode) ejects electrons
		In a vacuum they can travel to the collector (anode) giving a current
	Current emitted when light hit a metal was proportional to the light intensity
	Applying a positive voltage to the collector electrode increased the current to a plateau value
	A negative voltage decreased the current
	If the voltage was far enough negative, the current stopped completely (the stopping point)
	Increasing light frequency causes the stopping potential to move away from zero (become more negative)
	Decreasing light frequency causes the stopping potential to move closer to zero
	If the frequency is too low, there is no current at all for any collector voltage (threshold frequency)

