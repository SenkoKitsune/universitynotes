Terms for describing circuits

| Term             | Definition                                                                          |
| ---------------- | ----------------------------------------------------------------------------------- |
| Node             | A point where two or more circuit elements join                                     |
| Essential node   | A node where three or more circuit elements join                                    |
| Path             | A trace of adjoining basic elements with no elements included more than once        |
| Branch           | A path that connects two nodes                                                      |
| Essential Branch | A path which connects two essential nodes without passing through an essential node |
| Loop             | A path whose last node is the same as the starting node                             |
| Mesh             | A loop that does not enclose any other loops                                        |
| Planar circuit   | A circuit that can be drawn on a plane with no crossing branches                    |

Two nodes connected only by a wire with no additional circuit components are considered only one node

Kirchhoff's Current Law
	The algebraic sum of the currents entering a node (or a closed boundary) is 0
	The current entering a node may be regarded as positive while the currents leaving the node may be taken as negative
	KCL is based on the law of conservation of change
	Alternate statement of KCL:
		For lumped circuits, the algebraic sum of the currents leaving a node (or a closed boundary) is zero

A closed boundary is a closed curve (or surface), such as a circle in a plane (or a sphere in three-dimensional space) that has well-defined inside and outside boundaries
	This closed boundary is sometimes called a super node or a Gauss surface

Kirchhoff's Voltage Law
	The algebraic sum of the voltage drops around any closed (or loop) is zero at any instance of time

A series connection of two different current sources is impossible
A parallel connection of two different voltage sources is impossible

A current source supplying zero current is equivalent to an open circuit
A voltage source supplying zero voltage is equivalent to a short circuit

Series and parallel connections
	Two or more elements are connected in series when they are connected end to end with only one common node between the two consecutive elements, and the elements all carry the same current

The equivalent resistance of any number of resistors connected in series is the sum of the resistors
	$R_{eq} = R_1 + R_2 + ... + R_n$ or $\displaystyle \frac{1}{G_{eq}} = \frac{1}{G_1}+\frac{1}{G_2}+...+\frac{1}{G_n}$

Voltage Division
	In a series combination of n resistors, the voltage drop across the resistor $R_j$ for $j = 1,2,...,n$ is
		$\displaystyle v_j(t) = \frac{R_j}{R_1 + R_2 + ... + R_n}v_{in}(t)$

Two or more circuit elements are in parallel if they are connected between the two same nodes
	parallel elements have the same voltage

The equivalent resistance of any number of resistors connected in parallel is the sum of their individual conductance
	$G_{eq} = G_1 + G_2 + ... + G_n$ or $\displaystyle \frac{1}{R_{eq}} = \frac{1}{R_1}+\frac{1}{R_2}+... + \frac{1}{R_n}$

Current Division
	In a parallel combination of n resistors, the current through the resistor $R_j$ for $j = 1,2,...,n$ is
		$\displaystyle i_j(t) = \frac{G_j}{G_1+G_2+...+G_n}i_{in}(t)$

