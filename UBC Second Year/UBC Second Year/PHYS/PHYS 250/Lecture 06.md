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
