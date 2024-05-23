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
	For the $i$th particle, $KE_i = \dfrac{|\textbf{p}_i|^2}{2m} = \dfrac{p_{xi}^2 + p_{yi}^2 + p_{zi}^2}{2m} = \dfrac{\pi^2\hslash^2(n_{xi}^2+n_{yi}^2+n_{zi}^2)}{2mL^2}$
	Internal energy of the gas is all the individual $KE$s added together:
		$\displaystyle U = \sum_{i = 1}^{N}\dfrac{\pi^2\hslash^2(n_{xi}^2+n_{yi}^2+n_{zi}^2)}{2mL^2}$ 
		$\displaystyle = \sum_{i = 1}^{N}\sum_{j \in \set{x,y,z}}\dfrac{\pi^2\hslash^2n_{ji}^2}{2mL^2}$
		$\displaystyle U = \sum_{i = 1}^{3N}\dfrac{\pi^2\hslash^2n_{i}^2}{2mL^2}$
	So all sets $\set{n_1, \dots, n_i, \dots, n_{3N}}$ for which $\displaystyle\sum_{i = 1}^{3N}\dfrac{\pi^2\hslash^2n_{i}^2}{2mL^2} = U_0$, are microstates whose internal energy is $U_0$
	How many sets $\set{n_1, \dots, n_i, \dots, n_{3N}}$ there are for which $\displaystyle\sum_{i = 1}^{3N}\dfrac{\pi^2\hslash^2n_{i}^2}{2mL^2} = U$
		or rewritten, $\displaystyle\dfrac{2mL^2U}{\pi^2\hslash^2} = \sum_{i=1}^{3N}n_i^2$
		$r \equiv \dfrac{L}{\pi\hslash}\sqrt{2mU}$
		Then $\displaystyle\sum_{i=1}^{3N}n_i^2 = r^2$
	If the sum were over two terms, we would have $n_1^2 + n_2^2 = r^2$ which defines a circle  in the $n_1, n_2$ plane
	Over three terms, we would have $n_1^2 + n_2^2 + n_3^2 = r^2$ which defines a sphere in the $n_1, n_2, n_3$ plane
	There are $\dfrac{mUL^2}{\pi\hslash^2}$ states that have energy $U$ in a single-atom ideal gas with volume $L^3$

We now perform the math with the sphere now on a hyper-sphere with 3$N$ dimensions
	The surface area of a hyper-sphere with 3$N$ dimensions is $\dfrac{2\pi^{\frac{3N}{2}}}{\left(\dfrac{3N}{2} - 1\right)!}r^{3N - 1}$
	We divide by a factor of $2^{3N}$ to restrict ourselves to all-positive $n$
	Then we divide by $1^{3N-1} = 1$ to get the number of states, giving $\dfrac{2\pi^{\frac{3N}{2}}}{\left(\dfrac{3N}{2} - 1\right)!}r^{3N - 1}$ states
	And plugging in $r \equiv \dfrac{L}{\pi\hslash}\sqrt{2mU}$ we have
	$\dfrac{\pi^{\frac{3N}{2}}}{\left(\dfrac{3N}{2}-1\right)!}\left[\dfrac{L}{pi\hslash}\sqrt{2mU}\right]^{3N-1}$
	But we have overcounted by $N!$ (the number of ways to exchange $N$ atoms), since Ideal Gas molecules are indistinguishable, so:
	There are $\dfrac{\pi^{\frac{3N}{2}}}{N!\left(\dfrac{3N}{2}-1\right)!}\left[\dfrac{L}{pi\hslash}\sqrt{2mU}\right]^{3N-1}$ microstates of an ideal gas with $N$ atoms in volume $L^3$ and internal energy $U$

