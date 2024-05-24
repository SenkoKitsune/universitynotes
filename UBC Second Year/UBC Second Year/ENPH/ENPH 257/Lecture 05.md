Multiplicity: thermodynamics is all about probability
	Finding which macrostates are the most likely
	If a system starts in a much-less-likely state, it is very likely to end up in a more likely state
		Systems tend to move to states with higher multiplicity, $\Omega$
	It is nice to quantify $\Omega$ in order to predict the evolution of systems
		$\Omega_{total} = \Omega_A\Omega_B\Omega_C\Omega_D$
	Notice that $\ln(\Omega)$ is monotonic (linear, moving in same direction), so maximizing $\Omega$ as systems do by probability also maximizes $\ln(\Omega)$
		And $\ln(\Omega) = \ln(\Omega_A) + \ln(\Omega_B) + \ln(\Omega_C) + ...$
	Define $S \equiv k_b\ln(\Omega)$, where $k_b$ is a matter of convention

$\Omega_{U,V,N} = \dfrac{\pi^{\frac{3N}{2}}}{N!\left(\dfrac{3N}{2}-1\right)!}\left[\dfrac{L}{pi\hslash}\sqrt{2mU}\right]^{3N-1}$ 
Taking the log of the large N limit,
	$S = Nk\left[\ln\left(\dfrac{V}{N}\left(\dfrac{4\pi mU}{3Nh^2}\right)^\frac{3}{2}\right)+\dfrac{5}{2}\right]$

Two ways to expand an idea gas without raising $T$, and therefore not increasing $U$
	1) Doing work against a piston in an isothermal process
		$\Delta U = 0 \to \delta Q = -\Delta W = -Nk_bT\ln\left(\dfrac{V_2}{V_1}\right)$
			as derived from work calculation
			$\Delta Q = T\Delta S$
	1) Letting it expand freely
		$\Delta U = \Delta Q = \Delta W = 0$
	$S$ is a state variable, so $\Delta S$ must be the same for both processes
		$S = Nk\left[\ln\left(\dfrac{V}{N}\left(\dfrac{4\pi mU}{3Nh^2}\right)^\frac{3}{2}\right)+\dfrac{5}{2}\right] = Nk_b\ln(V) + f(U,N) \longrightarrow \Delta S = Nk_b\ln\left(\dfrac{V_2}{V_1}\right)$
	