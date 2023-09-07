Many important circuit applications use combination of capacitors and resistors to produce time dependent currents

When the switch is open:
	no current can flow in the circuit
	the charge and the voltage on the capacitor are both zero

Closed:
	charge = CV
	voltage across the capacitor is V
	no current flowing

Case 1: Charging a capacitor
	Initial charge q<sub>c</sub>(0) = 0
	Switch is open until t = 0
	Once the switch is closed, Kirchhoff's voltage rule gives:  $V - iR-\displaystyle\frac{q}{C}$ = 0
	Taking the derivative: $0 - R\displaystyle\frac{di}{dt} - \frac{1}{C}\frac{dq}{dt}$, but $i = \displaystyle\frac{dt}{dq}$
	Immediately after the switch is closed, the capacitor acts like a wire (short circuit). There is no charge on the capacitor so V<sub>c</su> and i(0+) = V/R
	Hence: $=R \displaystyle\frac{di}{dt} - \displaystyle\frac{1}{C}i = 0$ -> separation of variables -> $\displaystyle\frac{di}{i} = -\displaystyle\frac{1}{RC}dt$
	Integration -> $i(t) = i(0)e^{-\displaystyle\frac{t}{RC}}$


Case 2: Discharging a capacitor
	Switch is connected for a long time
		Capacitor charges up to the voltage
	Switch is suddenly flipped off at t = 0+
	Capacitor starts to discharge through R
	Kirchhoff's voltage rule gives: $\displaystyle\frac{q(t)}{C}-iR = 0$
	$\displaystyle\frac{q}{RC} == i = -\displaystyle\frac{1}{RC}dt$
	Solving for the charge q(t) on the capacitor with $q_0 = CV}
		$i = -dq/dt$ since q is decreasing
	$q(t) = q_0e^{-t/RC}$, $i(t) = i_0e^{-t/RC}$
	Both q and i decrease exponentially 

How long is very long?
	The relevant time scale τ = RC:
		I = $\displaystyle\frac{V}{R}(e^{-\displaystyle\frac{t}{RC}})$
		$I(t) = I_0e^{-\displaystyle\frac{t}{τ}}$

The current has decreased to 37% of its initial value at t = τ
	Very long means t >> τ = RC

Charging:
$q(t) = Q_f(1-e^{-(\displaystyle\frac{t}{RC})})$

[[PHYS 158 Lecture 08]]