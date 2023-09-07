$\displaystyle V_f-V_i=ΔV = \frac{ΔU}{q}=-\frac{\int_{i}^{f}\vec{F}\cdot d\vec{l}}{q}=-\int_{i}^{f}\vec{E}\cdot d\vec{l}$
If E is parallel to l, the displacement is in the same direction as the field $\to$ so that the field does he work and the potential decreases
If E is antiparallel to l, the displacement is in the opposite direction to the field so that something else does the work and the potential increases

Ensemble of point charges
The electric potential energy of a system of (fixed) point charges is equal to the work that must be done by an  external agent to assemble the system, bringing each charge in from infinity to its final position
	Interaction is taken in parts, so for 3 point charges
		$\displaystyle U = k_c(\frac{q_1q_2}{r_{12}})+k_c(\frac{q_1q_3}{r_{13}})+k_c(\frac{q_2q_3}{r_{23}})$
			1) Bring in $q_2$ in E field of $q_1$
			2) Bring in $q_3$ in E field of $q_1$ and $q_2$

Potential Energy of N point charges
	For the total potential energy of a system of point charges
		$\displaystyle U = k\sum_{i=1, j > i}^{N}\frac{q_iq_j}{r_{i]}}$ with $i\neq j$
			To avoid double counting we must keep $i\neq j$
		Alternatively we can introduce a factor of 1/2 and let both $i,j = 1 \to N$ but of course $j\neq i$
			$\displaystyle U = k\sum_{i=1,j=1}^{N}\frac{q_iq_j}{2r_{ij}}$ with $i\neq j$

Clicker 23.2:
$\displaystyle V_f-V_i = -\int_{i}^{f}\vec{E}\cdot d\vec{l}$
$f=\infty, V_{\infty}=0, i=r$
1) $r> R_c$
	$\displaystyle E(s)=\frac{kQ}{s^2}$
	$\displaystyle V(r) = \int_{r}^{\infty}\frac{kQ}{s^2}ds = kQ\int_{r}^{\infty}\frac{ds}{s^2} = kQ[-\frac{1}{s}]_{r}^{\infty}$
2) $R_b < r < R_c$
	$\displaystyle V(r) = \int_{r}^{\infty}E(s)ds = \int_{r}^{R_c}E(s)ds + \int_{R_c}^{\infty}E(s)ds$
		$\displaystyle = 0 + V_1(R_c)$
		$\displaystyle = \frac{kQ}{R_c}$ : independent of r

Calculating Capacitance
The SI unit is the Farad, F
C is the capacitance
C depends only on geometry
	$\displaystyle C = \frac{C}{ΔV}$
Relatively easy for highly symmetric cases
1) put a general charge Q on the conducting places (+Q on the solid core, -Q on the shield)
2) Calculate the electric field due to the charge using Gauss's law
3) Calculate the potential difference from the electric field
4) Calculate the capacitance
	$\displaystyle C = \frac{Q}{ΔV}$

[[PHYS 158 Lecture 18]]