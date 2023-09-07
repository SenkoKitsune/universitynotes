RLC circuits
Using Kirchhoff's loop voltage rule:
+q/C - L$\displaystyle\frac{di}{dt}$ -Ri = 0
But $i = -\displaystyle\frac{dq}{dt}$
	since $dq < 0$

$\displaystyle L\frac{d^2q}{dt^2} + R\frac{dq}{dt}+\frac{1}{C}q = 0$

R = 0 case
LC circuit
	generate current oscillations
$\displaystyle L\frac{d^2q}{dt^2}+\frac{1}{C}q = 0$
$q(t) = Q_0cos(ωt)$, where ω = $\displaystyle\sqrt{\frac{1}{LC}}$

i(t) = $\displaystyle\frac{-dq}{dt} = ωQ_0sin(ωt)$
	$i$ is the current through the inductor
	$i_{max} = ωQ_0$
	Charge and current both oscillate with the same frequency and are out of phase by 1/4 of a cycle
	Current $i(t)$ and voltage $V(t) = q(t)/C$ are out of phase

Conservation of energy
At t = 0, all the energy is stored in the capacitor and none in the inductor $i=0$
At t = π/(2ω), all the energy is stored in the inductor (Q = 0), and $i$ is maximised
	$U_c = \displaystyle\frac{1}{2}\frac{Q^2}{C}$
	$\displaystyle U_L = \frac{1}{2}LI^2$
In the capacitor the energy is stored in the electric field $\vec{E}$ while the inductor the energy is stored in the magnetic field $\vec{B}$
	$\displaystyle u_E = \frac{ε_0}{2}\vec{E}^2$
	$\displaystyle u_B = \frac{1}{2μ_0}\vec{B}^2$

Let R -> 0 then
	$q(t) = Q_0cos(ωt + φ)$

RLC Circuits
	generate damped current oscillations
	$\displaystyle L\frac{d^2q}{dt^2} + R\frac{dq}{dt}+\frac{1}{C}q = 0$
	$\displaystyle q(t) = Ae^{-λ't}cos(ς't + Φ)$
	$\displaystyle ω' = \sqrt{(\frac{1}{LC}-\frac{R^2}{4L^2})}$
	$\displaystyle λ' = \frac{R}{2L}$

AC Current
the electrical voltage/current delivered to our houses oscillates at 60 Hz
AC voltage and current
$V^2(t) = V^2_{maz}sin^2(ωt) = (1/2)(1-cos(2ωt))V^2_{max}$
over N periods, cos(2ωt) averages to 0 so
$V^2{RMS} = <V^2(t)> = (1/2)V^2_{max}$

$I_{RMS} = (1/\sqrt{2})I_{max}$

[[PHYS 158 Lecture 10]]