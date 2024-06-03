Wave equation: $\dfrac{\partial^2 y}{\partial x^2} = \dfrac{1}{v^2}\dfrac{\partial^2 y}{\partial t^2}$ for $y(x,t)$
	Second order in both time and space
	Solution: $y(x,t) = f(x \pm vt)$ for any $f(\text{one argument})$
		If solution is a sinusoid with wavelength $\lambda$ and period $T$
			$y(x,t) = A\sin\left[  2\pi\left(\pm\dfrac{x}{\lambda}-\dfrac{t}{T}\right) + \phi \right]$ with $v = \dfrac{\lambda}{T}$
		It's convenient to write the sinusoid solutions as
			$y(x,t) = A\sin[\pm k = \omega t + \phi]$ with $k = \dfrac{2\pi}{\lambda}$ and $\omega = \dfrac{2\pi}{T} = 2\pi f$
				Putting the minus sign on $\omega t$ makes the wave direction have the same sign as $k$
				To satisfy the wave equation we still require $v = \dfrac{\lambda}{T} = \dfrac{2\pi/k}{2\pi / \omega} = \dfrac{\omega}{k}$
$p = \hslash k$
$E = \hslash\omega$

Schrödinger's Equation for a free particle in 1 dimension
	$i\hslash \dfrac{\partial y}{\partial t} = \dfrac{-\hslash^2}{2m}\dfrac{\partial y^2}{\partial x^2}$ gives $E \cdot y(x,t) = E \cdot y(x,t)$
	It's convenient to use $\psi(x,t)$
		$i\hslash \dfrac{\partial \psi}{\partial t} = \dfrac{-\hslash^2}{2m}\dfrac{\partial^2 \psi}{\partial x^2}$
	Alternative solution form
		Start with $\psi(x,t) = \exp[i\cdot(kx - \omega t)]$
		Using $k = \dfrac{p}{\hslash}$ and $\omega = \dfrac{E}{\hslash}$
			$\psi(x,t) = \exp\left[i\cdot\dfrac{px-Et}{\hslash}\right]$
	The equation is linear

Momentum operator
	$p_{op} = \dfrac{\hslash}{i}\dfrac{\partial}{\partial x}$

We can write Schrödinger as $i\hslash \dfrac{\partial \psi}{\partial t} = \dfrac{-\hslash}{2m}\dfrac{\partial^2 \psi}{\partial x^2} = \dfrac{p_{op}^2}{2m}\psi$

$\psi^*\psi$ is the probability density if $\displaystyle \int_{-\infty}^{\infty}\psi^*\psi\cdot dx = 1$

Fourier Analysis
	Decomposing a data set or function into a sum or intergral of sinusoidal function
	For $N$ discrete samples $x_j$, the transform $x_k$ is
		$\displaystyle X_k = \sum_{j = 0}^{N - 1}x_j\exp\left[-2\pi i \dfrac{jk}{N}\right]$, $j,k$ are indices, $i = \sqrt{1}$
		Even if the $x_j$ are real, the transform $X_j$ is complex
	The inverse transform is
		$\displaystyle x_{j} = \sum{j = 0}^{N - 1}X_k\exp\left[2\pi i \dfrac{jk}{N}\right]$


The continuous equivalent, in the signal-processing convention:
	$\displaystyle S(f) = \int_{-\infty}^{\infty}s(t)\exp[-2\pi i ft]$
	$\displaystyle s(f) = \int_{-\infty}^{\infty}S(t)\exp[2\pi i ft]$

For quantum mechanics:
	$\displaystyle y(x) = \int_{-\infty}^{\infty}dk\cdot a(k) \exp(ikx)$
	$\displaystyle a(k') = \frac{1}{2\pi}\int_{-\infty}^{\infty}dx\cdot y(x)\exp(-ik'x)$
	
Heisenberg Uncertainty Principle
	Consider $a(k) = \dfrac{1}{\sqrt{2\pi}\sigma_k}\exp\left[\dfrac{-k^2}{2\sigma^2_k}\right]$
		This is a Gaussian in $k$-space, centred on $k=0$ width $\sigma_k = \dfrac{1}{\sigma_x}$
		$\sigma_x, \sigma_p \geq \dfrac{\hslash}{2}$
	Gaussian wave functions are minimum uncertainty and give you the lower limit
	The wave packet spreads in $x$-space, but it stays the same width in $k$-space, so we only get the minimum product at $t=0$

We include forces by adding a potential energy function ,$V(x)$, also times the wave-funtion:
	$i\hslash\dfrac{\partial}{\partial t}y(x,t) = \dfrac{-\hslash}{2m}\dfrac{\partial^2}{dx^2}y(x,t) + V(x)\cdot y(x,t)$

The potential is (minus) the integral of force over distance
	A constant force gives a linear potential:
		$F \to V(x) = -F \cdot x$
	The solutions for that to be the Airy function
	A restoring force proportional to distance gives a quadratic:
		$F(x) = -kx \to V(x) = \dfrac{1}{2}kx^2$

The step potential
	Simplest cases: potential is zero at $x < 0$ and steps to a different value for $x > 0$, then maybe steps back
	Classically if a particle comes in from the left with energy E, and $V > E$, the particle will bounce back
	If $V < E$, the particle will continue to positive $x$, but at reduced velocity