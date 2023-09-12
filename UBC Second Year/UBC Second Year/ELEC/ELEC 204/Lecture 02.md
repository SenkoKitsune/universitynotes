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
	This closed boundary is sometimes called a supernode or a Gauss surfacce

