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
		4) Write the relationship between th