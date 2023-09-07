Sign convention for emfs
+E travel direction from - to + and -E from + to -


A capacitor is any collection of conductors which stores charge and therefore energy

Capacitors need to be charged
	Not a source of constant potential (V)
	Very high voltages possible
	No internal resistance -> fast discharge and the voltage changes during discharge

Batteries are sources of potential (V):
	Constant potential difference created bu separating charges in electro-chemical reactions
	Limited to low volatges.
		High voltage = batteries in series
	Internal resistance leads to a maximum current that a battery can deliver  
		ΔU = qΔd

Capacitance
	Q ~ ΔV
	Q<sub>n</sub>

Capacitor in circuits: Connected in Parallel
	Combination of capacitors can yield a capacitor that can store a higher total charge
	You can replace the combination with a equivalent capacitor that has the same capacitance
	Potential difference due to the battery is the same across each capacitor
	Total charge Q<sub>P</sub> = $\displaystyle\sum_{i=1}^{n}Q_i$

Capacitors in circuits: Connected in Series
	Combination of capacitors can also yield a capacitor that can store the same total charge as a single capacitor
		Each capacitor stores the same charge Q
	Only two plates are connected to the battery. The other plates are electrically isolated from the rest of the circuit. The battery cannot deposit any charge there. There is only the induced charged on the isolated plates
	The magnitude of the charge on each plate must be the same to yield a net charge of zero on the isolated plates - even if the capcitors have totally different values of capacitance
	Q<sub>S</sub> = Q<sub>1</sub> + Q<sub>2</sub> + ...
	= $\displaystyle\sum_{i=1}^{n}\displaystyle\frac{Q}{C_i}$

Energy storage in capacitors
	Given a potential difference ΔV, the work done by the EMF to move a small charge +dq from the lower plate to the upper plate = 
		dW = dU = dqΔV
		We also know q = CΔV so dW = dq ΔV = dq (q/C)
	Total work is just the integral of dW so
		W = $\displaystyle\int_{0}^{Q_f}dq\displaystyle\frac{q}{C} = \displaystyle\frac{1}{2}\displaystyle\frac{Q^2_f}{C} = \displaystyle\frac{1}{2}CV_f^2$

[[PHYS 158 Lecture 06]]