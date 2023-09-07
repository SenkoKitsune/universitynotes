Divergence of a vector
	div$\vec{E} = \nabla\cdot\vec{E}$
	$\displaystyle \nabla\cdot\vec{E} = \left(\frac{\partial}{\partial x}, \frac{\partial}{\partial y}, \frac{\partial}{\partial z}\right)\cdot (E_x,E_y,E_z)= \left(\frac{\partial E_x}{\partial x}, \frac{\partial E_y}{\partial y}, \frac{\partial E_z}{\partial z}\right)$
Curl of a vector
	curl$\vec{E} = \nabla\times\vec{E}$
	$\displaystyle \nabla\times\vec{E}=\left(\frac{\partial}{\partial x}, \frac{\partial}{\partial y}, \frac{\partial}{\partial z}\right)\times (E_x,E_y,E_z) = \det\begin{bmatrix}\hat{i} & \hat{j} & \hat{k} \\ \partial_x & \partial_y & \partial_z \\ E_x & E_y & E_z\end{bmatrix}$

Light from Maxwell's equations
	Assume empty space
	Combine Ampere's law and Faraday's law into single equation
	$\displaystyle \nabla \times \vec{B} = μ_0ε_0\frac{\partial \vec{E}}{\partial t} \to \nabla\times\nabla\times\vec{B} = μ_0ε_0\nabla\times \frac{\partial \vec{E}}{\partial t}$
	Use vector identity $\nabla\times\nabla\times \vec{a} = \nabla (\nabla\cdot\vec{a})-\nabla^2\vec{a}$ valid for any vector to simplify the LHS and exchange $\nabla$ with the time derivative on the RHS
		$\displaystyle \nabla^2=\left(\frac{\partial^2}{\partial x^2} + \frac{\partial^2}{\partial y^2} + \frac{\partial^2}{\partial z^2}\right)$
	We obtain
	$\displaystyle \nabla(\nabla\cdot\vec{B})-\nabla^2\vec{B} = μ_0ε_0\frac{\partial \vec{E}}{\partial t}(\nabla\times\vec{E})$
	From Gauss's law we know that $\nabla\times\vec{B} = 0$ and we know from Faraday's law that $\displaystyle \nabla\times\vec{E} = -\frac{\partial \vec{B}}{\partial t}$
		$\displaystyle \nabla^2\vec{B} = \frac{1}{c^2}\frac{\partial^2 \vec{B}}{\partial t^2}$
		$\displaystyle c = \frac{1}{\sqrt{μ_0ε_0}}$
		$B_z(x,t) = B_0\cos(kx-ωt)$
			$ω/k = c$
		We can now get  the electric field from $\displaystyle \nabla \times \vec{B} = μ_0ε_0\frac{\partial \vec{E}}{\partial t}$
			$\displaystyle \nabla\times\vec{B} = \det\begin{bmatrix}\hat{i} & \hat{j} & \hat{k} \\ \partial_x & \partial_y & \partial_z \\ 0 & 0 & B_z(x,t)\end{bmatrix} = -\hat{j}\partial_x B_z(x,t)$
			$E_y(x,t) E_0\cos(kx - ωt)$
				$E_0 = c^2B_0$
		EM waves are transverse
			Bothe $\vec{E}$ and $\vec{B}$ fields are perpendicular to the direction of propagation

Propagation of electromagnetic waves
	The wave is transverse, moving at unchanging speed $c$ in a vacuum, with electric and magnetic fields in a definite ration, and requiring no medium (like water or air)
	Direction of propagation is the direction of $\vec{E} \times \vec{B}$

Speed of light $c$ is $2.99 \times 10^8$ m/s in a vacuum
	More generally in a medium, the speed is 
		$\displaystyle c_{med} = \frac{1}{\sqrt{με}} = \frac{c}{n}$
		$\displaystyle c = \frac{1}{\sqrt{μ_0ε_0}}$
	This slowdown can be explained from dielectric and magnetic properties of the medium encoded in constants ε and μ

EM waves may often be treated as plane waves
	Far enough from the source and considering one polarization of the vector planes only, the representations of electric and magnetic fields may be treated as orthogonal plane waves over a small region in space. In this case, E $\approx$ constant over a plane
		Wave energy spreads over a sphere - intensity = $1/r^2$

Energy in an EM wave, the Poynting vector
	The energy in an electromagnetic wave can be considered by thinking of energy densities
		$\displaystyle \vec{u} = \frac{ε_0\vec{E}^2}{2} + \frac{\vec{B}^2}{2μ_0} = \frac{ε_0\vec{E}^2}{2}+\frac{\left(\sqrt{ε_0μ_0}\vec{E}\right)^2}{2μ_0}$
		$\displaystyle \vec{u} = \frac{ε_0\vec{E}^2}{2} + \frac{ε_vec{E}^2}{2} = ε_0\vec{E}^2=\frac{\vec{B}^2}{μ_0}=\frac{\vec{E}\vec{B}}{μ_0c}$
		$\displaystyle \vec{S} = \frac{\vec{E}\times\vec{B}}{μ_0}$
	Solar wind: there is pressure exerted by light
		Poynting Vector S = rate of Energy flow = Power/Area
		$\displaystyle \vec{S} = \frac{\vec{E}\times\vec{B}}{μ_0}$
		$S_{avg}=\frac{E_{max}B_{max}}{2μ_0} = I$
			I = intensity of the wave
		Radiation pressure
			$\displaystyle P_{rad} = \frac{I}{c} = \frac{S_avg}{c}$

Electromagnetic waves occur over a wide range of frequencies

Generation of EM Waves
	Anytime charges are moving in a periodic fashion, EM waves are generated

Standing EM waves
	An EM wave can be reflected so waves can add constructively and resonate in a cavity

Quantum Picture
	Treat light as composed of particles - photons
		Number of photons in $5 mW$ beam ~$10^{16}$
		Energy of 1 photon $\displaystyle E_γ = hf = \frac{hc}{λ}$ 
			h is Planck's constant
	Particle-wave duality (also true for electrons, protons, etc) underlies the subject for Quantum Mechanics

Theory of relativity
	Speed of light is constant in all reference frames