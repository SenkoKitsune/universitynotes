AC circuit: purely "R" = resistive
$v(t) = V_{max} sin(ωt)$
$V(t) = i(t)R = 0$
$i(t) = V(t)/R = (V_{max}/R)sin(ωt)$


AC circuit: purely "L" = inductive
$V(t) - L di/dt = 0$
$V_{max}sin(ωt) - Ldi/dt = 0$
$di/dt = (V_{max}/L)sinωt$
$i(t) = -(V_{max}/ωL)cos(ωt) = I_{max}sin(ωt-π/2)$

The current through the inductor is π/2 out of phase with voltage


$V_L$ leads $i_L$ or $i_L$ lags behind $V_L$
$I_{max} = V_{max}/ωL$
$V_{max}=ωLI_{max}= X_LI_{max}$
V_{max} and I_{max} do not occur at the same time
Inductive reactance
	$X_L = ωL $is measured in Ohms


AC Circuit: purely "C" = capacitive
V_C lags behind $i_C$ or $i_C$ leads $V_C$

$\displaystyle V(t)-\frac{q(t)}{C} = 0$
$V_{max}sin(ωt) - \displaystyle\frac{q(t)}{C}=0$
$q(t) = C V_{max}sin(ωt)$
$\displaystyle i(t) = \frac{dq}{dt} = (ωC)V_{max}cos(ωt)$
$i(t) = (V_{max}/X_C)sin(ωt+π/2)$
$I_{max} = V_{max}ωt$

$X_C = 1/ωC$
Capacitive reactance $X_C = 1/ωC$ is measured in Ohms
$V_{max}$ and $I_{max}$ do not occur at the same time

Phasor diagrams
Length of phasor equals maximum current I
Phasor rotates with frequency *f* and angular speed $ω = 2πf$
Projection of phasor onto the horizontal axis at time t equals to current i at that instant $i = Icos(ωt)$

$i(t) = O_{max}cos(ωt)$
"R": resistor voltage is in-phase with current
	current and voltage phasors are in phase:
		they rotate together

"L": inductor voltage leads current
Voltage phasor leads current phasor by $Φ = π/2$ rad $= 90^o$

"C": capacitor lags current
Voltage phasor lags current phasor by $Φ = -π/2$ rad $= -90^o$

AC-RLC circuit
The impedance triangle
Source voltage phasor is the vector sum of the $V_R$, $V_L$, and $V_C$ phasors
	V = IZ
Inductor voltage leads current phasor by $90^o$ 
	$V_L = IX_L$
All circuit elements have the same current phasor
	Resistor voltage phasor is in phase with current phasor
		$V_R = IR$
Capacitor voltage lags current phasor by $90^o$. It is thus always antiparallel to the $V_L$ phasor
	$V_C = IX_C$
	
$i(t) = I_{max}cos(ωt)$
$v(t) = V_{max}cos(ωt+Φ)$

$V^2 = (V_R)^2+(V_L-V_C)^2$
$V^2=(I_{max})^2((X_R^2+(X_L-X_C)^2) = (I_{max})^2|Z|^2$

$|Z|^2 = (R^2+(X_L-X_C)^2) = R^2+(ωL-\displaystyle\frac{1}{ω}{C})^2$
The angle between the voltage V and the current I = Φ where 
	$tan(Φ) = \displaystyle\frac{X_L-X_C}{R}$

Voltage: peak vs instantaneous values
Peak values:
	$V^2= (V_R)^2+(V_L-V_C))^2$
	They do not occur at the same time

Impedance triangle via Complex numbers
Imaginary j axis
$j^2 = -1$
	Phasors are just rotating vectors

$V=IZ$
$V_R = IR$
$V_Z = I(X_L-X_C)$

[[PHYS 158 Lecture 11]]