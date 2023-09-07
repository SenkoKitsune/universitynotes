An electric circuit is an interconnection of electrical components

Electric charge is the basis for describing all electrical phenomena
	Charge is an electrical property of the atomic particles of which matter consists and is measured in coulombs

The charge of an electron is equal to that of an proton and is 
	$e = 1.602 \times 10^{-19}C$

In 1 C of charge, there are $6.24 \times 10^{18}$ electrons
	Laboratory values of charges are more likely to be a fraction of a coulomb
		$pC, μC$

Law of conservation of charge: charge can neither be created or destroyed

Conductor: a material in which charges can move to neighbouring atoms with relative ease
	One measure of this relative ease of charge movement is the electric resistance of the material
		In metals, the only charged particles that can move are electrons
Insulators: a material that opposes the charge movement (ideally infinite opposition)
Semi-conductors: a material whose conductive properties are somewhat in between those of conductors and insulators

Current: rate of flow of charge across any cross section of a conductor, measured in Amperes

Current can be thought of as the rate of change of charge
	$\displaystyle i = \frac{dq}{dt}$
The direction of the current is the direction of movement of positive charges

Two types of currents: direct and alternating
	Direct current (DC) is a current that remains constant with time
	Alternating current (AC) is a current that varies constantly with time

Voltage (electromotive force, or potential) between two points is the energy required per unit charge to move a given charge from one point to the other (through a circuit element) and is measured in Volts
	$\displaystyle v = \frac{dW}{dq}$
	Similar to electric currents, there are two important types of voltage: DC and AC

Voltage polarity:
	The plus (+) and minus (-) sign are used to define voltage polarity
		The assumption is that the potential of the terminal with (+) polarity is higher than the potential of the terminal with (-) polarity by the voltage drop

Power: the rate of change of energy per unit time, measured in watts
	$\displaystyle p = \frac{dW}{dt}=\frac{dW}{dq}\times\frac{dq}{dt}=vi$

Passive sign conversion
	For calculating absorbed power: the power absorbed by any circuit element with terminals A and B is equal to the voltage drop from A to B multiplied by the current through the element from A to be
		$P = V_{ab}\times I_{ab}$

With this convention, if $P \geq 0$, then the element is absorbing power

Principle of conversion of the power
	The algebraic sum of the powers absorbed by all elements in a circuit is zero at any instant of time
		$\displaystyle \sum{P} = 0$

Energy
Instantaneous power: $p(t) = v(t)i(t)$
	Energy absorbed or supplied by an element can different from time $t_0$ from time $t_0$ from time to time
		$t > t_0$
		$\displaystyle W = W(t_o, t) = \int){t_0}{t} P(τ)dt = \int{t_0}{t} v(τ)i(τ)$
	
Independent sources: An (ideal) independent source is an active element that provides a specified voltage or current that is independent of other circuit elements and/or how the source is used in the circuit

Current source: equivalent representation of ideal independent current sources whose current $i(t)$ is maintained under all voltage requirements of the attached circuit

Ideal dependent (controlled) source is an active element whose voltage or current is controlled by a voltage or current of another circuit element.
	Essential to mathematical models used to describe the behaviour of many electronic circuit elements

Dependent sources are usually presented by diamond-shaped symbols

Four types of dependent sources
	1) Voltage-controlled voltage source (VCVS)
		$V_s(t) = αV(t)$
			where $V(t)$ is the voltage on another electronic component
	2) Current-controlled current source (CCCS)
		$V_s(t) = βI(t)$
	3) Voltage-controlled current source (VCCS)
		$I_s(t) = γV(t)$
	4) Current-controlled current source (CCCS)
		$I_s(t) = δI(t)$

Resistance:
	Different material allow charges to move within them with different le