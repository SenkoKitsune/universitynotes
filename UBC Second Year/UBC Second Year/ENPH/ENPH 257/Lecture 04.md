Quantization in quantum mechanics
	Quantum mechanically, the radius and energies of orbits are quantized (discrete)
	At the most rudimentary level, because electrons are waves
	There is a phase-matching condition for electron orbits, just like for standing waves on a string/in a tube
	Phase-matching in an orbit is equivalent to boundary conditions in the standing-wave problem in acoustics
	The wave nature of electrons is encapsulated in it's wavefunction, often called $\psi$ or $\phi$
	$\psi$ assigns an amplitude and a phase to every possible characteristic of the particle
	The amplitude of $\psi$ is related to how likely it is to find the particle with that characteristic ($|\psi|^2$ is the probability density of the characteristic)
	There is a "wave equation" that governs EM waves: $\nabla^2\vec{E}\propto \dfrac{d^2\vec{E}}{dt^2}$, and nearly identical one that governs string/acoustics
	The wave equation that governs $\psi$ is the Schrödinger Equation
		$\hat{H}\psi = i\hslash \dfrac{d\psi}{dt}$, $\hslash = \dfrac{h}{2\pi}$
		Where $\hat{H}$ is the Hamiltonian and in the simplest case $\hat{H} = \nabla^2$

$i\hslash\dfrac{\delta}{\delta t}\psi(x,t) = -\dfrac{\hslash^2}{2m}\dfrac{\delta^2}{\delta x^2}\psi(x,t)+ V(x)\psi(x,t)$ 1D Schrödinger Equation
	$i\hslash\dfrac{\delta}{\delta t}\psi(x,t) = \hat{H}\psi(x,t)$ where $\hat{H} = -\dfrac{\hslash^2}{2m}\dfrac{\delta^2}{\delta x^2}+V(x)$
	$V(x) = \begin{equation*}\left\{ \begin{aligned}\infty &&  x \leq \dfrac{-L}{2} \\ 0 &&  \dfrac{-L}{2} < x < \dfrac{L}{2} \\ \infty &&  x \geq \dfrac{L}{2} \end{aligned}\right.\end{equation*}$
	A hard-wall box from $\dfrac{-L}{2}$ to $\dfrac{L}{2}$

Quantum states enumerated by "$n$" for each dimension
	$\lambda_{n_x} = \dfrac{2L}{n_x}, \lambda_{n_y} = \dfrac{2L}{n_y}, \lambda_{n_z} = \dfrac{2L}{n_z}$
		Assume $L$ is the same in each dimension for simplicity
	Momentum $p = \dfrac{2\pi\hslash}{\lambda}$
	Kinetic energy $\dfrac{p^2}{2m}$
	The kinetic energy of a particle is $KE = \dfrac{|\textbf{p}|^2}{2m} = \dfrac{p_x^2 + p_y^2 + p_z^2}{2m} = \dfrac{\pi^2\hslash^2(n_x^2+n_y^2+n_z^2)}{2mL^2}$
	For the $i$th particle, 