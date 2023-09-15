Wheatstone Bridge
	accurate device for measuring resistance
	Centre leg of the circuit contains a galvanometer ( a very sensitive device used to measure current)
	When the unknown resistor is connected to the bridge, $R_3$ is adjusted until the current in the galvanometer, at which the bridge is balanced

Wye-Delta
	Y & Δ networks are said to be balanced when $R_1=R_2=R_3=R_Y$ & $R_A=R_B=R_C=R_Δ$
	$\displaystyle R_1 = \frac{R_BR_C}{R_A+R_B+R_C}$
	$\displaystyle R_2 = \frac{R_AR_C}{R_A+R_B+R_C}$
	$\displaystyle R_3 = \frac{R_AR_C}{R_A+R_B+R_C}$

Two popular and powerful techniques for analysing circuits are:
	Nodal analysis: a general procedure to find all the node voltages in a circuit
		Based on KCL and Ohm's Law
	Mesh analysis: another general procedure to find mesh currents which circulate around closed paths in the circuit
		Based on KVL and Ohm's Law

Modified Nodal Analysis (MNA)
	Not as popular as the first two, more powerful

Reference node or ground
	A node that is assumed to have a zero potential
		If the reference node is not explicitly indicated on the circuit one can arbitrarily choose any node as the ground

Node voltage
	The voltage difference/drop from a give node to the reference node

Regular modal analysis:
	Steps to determine the node voltages for a circuit with no floating voltage source:
		1) Select a reference node: A floating voltage source is a voltage source that neither of its terminals is connected to the reference node
			None of the terminals are grounded
			Pick the node with most connections as reference node
		1) Assign voltages to other nodes. these node voltages are referenced to the reference node
		2) Write KCL for all unknown non-reference nodes. When possible, use Ohm's law to relate the branch currents to node voltages
		3) Solve the resulting system of equations for unknown node voltages

Floating Voltage sources
	Form a super-node which is formed by enclosing the floating voltage source (independent or dependent) and any elements in parallel with it in a closed boundary

