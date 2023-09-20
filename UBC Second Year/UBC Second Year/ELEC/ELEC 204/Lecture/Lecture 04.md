Loop and Mesh analysis

Mesh analysis is a special case of a more general technique called loop analysis
A mesh is a loop that does not contain any other loops within it
Mesh analysis is not quite as general as nodal analysis since it can only be applied to planar circuits
A planar circuit is a circuit that can be drawn in a plane with no branches crossing one another

Number of linearly independent loops
	IN a circuit with B branches and N nodes there are N-N+1 linearly independent loops
	Number of independent loops is equal to the number of meshes

Modified Nodal Analysis

| True node   | essential node is the point of connection of three or more circuit elements                                                    |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Binary node | has only two components connected to it                                                                                        |
| Branch      | collection of elements that are connected between two true nodes that includes only those two true nodes (no other true nodes) | 

For modified nodal analysis (MNA)
	Four general types for branches

| R branch | Resistor                    |
| -------- | --------------------------- |
| RV       | Resistor and Voltage source |
| I | Current source in series with other components              |
| V         |   Voltage                          |

Modified Nodal Analysis
	Unknowns
		1) Controlling variables (for dependent sources)
		2) Current in V branches
		3) Voltage of each true node
	MNA steps
		1) Identify every true node of the circuit
		2) Choose one of them as a reference node (node whose voltage is zero)
		3) Write one equation per controlling current or voltage of dependant sources
		4) Write the relationship between the two nodes of the V branch
		5) Write one KCL per true node

Linearity
	A linear circuit (or in general a linear system) is a circuit (system) whose output is linearly related (or directly proportional) to its input
	A system is linear only and only if it has these two properties
		1) If the input of the system is multiplied by a constant then the output is also multiplied by a same constant (**Homogeneity**)
		2) The output of the system to a sum of inputs is the sum of the outputs to each input applied separately (**Additivity**)

In circuit theory, the inputs of a circuit are usually the independent voltage or current sources and the outputs are the voltages or currents of some elements of the circuit

Linearity Theorem
	For any linear circuit, any output voltage or current, denoted by variable $y$, is related linearly to the independent sources of the circuit, i.e.
		$y = a_1u_1+a_2u_2+\dots+a_mu_m$
		where $u_1$ through $u_m$ are voltages and current values of the independent sources in the circuit and $a_1$ through $a_m$ are properly dimensioned constants

Proportionality Property
	In a linear circuit, when only one independent source is acting (alone), the output is proportional to that input (refer to linearity theorem). Since the system is linear, if the input is multiplied by a constant, then the output is multiplied by the same constant

