Forced oscillation 

Damped case $c > 0$
	$m\prime\prime + cx\prime + kx = F_0cos(\omega t)$
	Here, $x_c(t)$ is one of the following forms
		$0 < c < \sqrt{4mk}$, $\displaystyle x_c(t) = e^{-pt}\left(c_1\cos(\omega_1t)+c_2\sin(\omega_1t)\right)$, where $\displaystyle p = \frac{c}{2m}, \omega_1 = \frac{1}{2m}\sqrt{4mk - c^2}$
			Underdamped
		$\displaystyle c = \sqrt{4mk}$, $x_c(t) = e^{-pt}(c_1+c_2t)$
			Critically damped
			
$x(t) = x_c(t) + x_p(t)$, $x_c(t$) = exp decay, $x_p(t)$ remain for all $t$

Partial resonance: even when there is damping we expect to have some sort of resonance when $0 < c << 1$ and $\omega \sim \omega_0$
	For $m\prime\prime + cx\prime + kx = F_0cos(\omega t)$
		We can show that
			$\displaystyle x_p(t) = \frac{F_0}{m\sqrt{(2\omega p)^2+(\omega_0^2-\omega^2)^2}}\cos(\omega t - \delta)$, $\displaystyle p = \frac{c}{2m}, \omega_0 = \sqrt{\frac{k}{m}}$
				$x_p(t) = A\cos(\omega t) + B\sin(\omega t)$
			$\omega_{max} = \sqrt{\omega_0^2 - \frac{c^2}{2m^2}}$
			When $\omega = \omega_{max}$, we say there is practical resonance in the system