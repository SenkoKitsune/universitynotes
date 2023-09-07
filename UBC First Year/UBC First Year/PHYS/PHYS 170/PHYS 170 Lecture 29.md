A force $\vec{F}$ does work on a particle only when the particle undergoes a displacement in the direction of the force

The displacement is
$d\vec{r} = \vec{r}'-\vec{r}$
and the magnitude of the displacement is $ds$
The infinitesimal word $dU$ done by $\vec{F}$ over this interval is a scalar quantity given by 
	$dU = Fds\cos(θ)$
	Where $θ$ is the angle between $d\vec{r}$ and $\vec{F}$

$dU = \vec{F}\cdot d\vec{r}$

$dU$ can be positive, negative, or 0 as follows:
1) $0^o \leq θ < 90^o: \cos(θ) > 0$: Force and displacement vectors have same sense; work is positive
2) $90^o < θ \leq 180^o: cos(θ) < 0$: Force and displacement vectors have negative sense; work is negative
3) $θ= 90^o: cos(θ) = 0$: Force and displacement vectors are perpendicular; no net work

Work of a force:
Force as a function of $s$:
	$\vec{F} = \vec{F}(s)$
	We denote the finite amount of work done by the force as $U_{1-2}$ and compute t using
		$\displaystyle U_{1-2}=\int_{\vec{r}_1}^{\vec{r}_2}\vec{F}\cdot d\vec{r} - \int_{s_1}^{s_2}F\cos(θ)ds$

Work of a constant force along a straight line
	$\vec{F}$ is a constant vector, $\vec{F} = \vec{F}_c$
	$\displaystyle U_{1-2}=F_c\cos(θ)\int_{s_1}^{s_2}ds$
	$\displaystyle U_{1-2} = F_c\cos(θ)(s_2-s_1)$
	$U_{1-2}=F_c\cos(θ)Δs$

Work of a weight
Consider a particle with weight, W, moving up along a path parameterized by $s$ from position $s_1$ to $s_2$
	At any point along the path, the infinitesimal displacement, $d\vec{r}$ 
	$\displaystyle d\vec{r} = d_x\hat{i} + d_y\hat{j}+d_z\hat{k}$
We have $W = -W\hat{j}$, so the work done by the weight is
	$\displaystyle U_{1-2} = -\int_{y_1}^{y_2}Wdy = -W(y_2-y_1)$

Work of a spring force:
	Work done on a spring by a force:
	$F_s = ks$
		$\displaystyle U_{1-2} = \int_{s_1}^{s_2}F_sds=\int_{s_1}^{s_2}ksds=\frac{1}{2}ks_2^2-\frac{1}{2}ks_1^2$
	Force acting on a particle:
		The force, $F_s$ on the particle now always acts in the opposite direction of the spring
$\displaystyle U_{1-2} = -\int_{s_1}^{s_2}F_sds=-\int_{s_1}^{s_2}ksds=-\left(\frac{1}{2}ks_2^2-\frac{1}{2}ks_1^2\right)$
Consider a particle moving along some path with position, velocity, acceleration, and forces acting on it defined with respect to an inertial coordinate system
	At some instant of time, the particle is at location $P$, with resultant force $\vec{F} =\sum\vec{F}$ acting on it
	We can introduce tangential and normal coordinates $(t,n)$ at P and consider the EOM in the $t$ direction
		$\sum F_t = ma_t$
	$a_tds = v dv$
	We multiply both sides of this equation by $m$ and integrate along the path from
	1) Where $s=s_1$ and $v=v_1$ to
	2) Where $s = s_2$ and $v=v_2$
	Thus we have:
		$\displaystyle \int_{s_1}^{s_2}ma_tds = \int_{v_1}^{v_2}mvdv$
	We can manipulate the last equation as follows:
		$\displaystyle \int_{s_1}^{s_2}ma_tds = \int_{v_1}^{v_2}mvdv$
		$\displaystyle \int_{s_1}^{s_2}(ΣF_t)ds=\frac{1}{2}mv_2^2-\frac{1}{2}mv_1^2$

Principle of work and energy (PWE)
	$\displaystyle ΣU_{1-2}=\frac{1}{2}mv_2^2-\frac{1}{2}mv_1^2$

$\displaystyle T = \frac{1}{2}mv^2$ = kinetic energy of particle

Principle of work and energy
	$\displaystyle T_1 + ΣU_{1-2} = T_2$
	The initial kinetic energy of the particle plus the work done by all of the forces acting on the particle as it moves from its initial to final position is equal to the final kinetic energy of the particle

PWE for a system of particles
	Consider the $i^{th}$ particle, with mass $m_i$ and acted on by the forces:
		$\vec{F}_i$ = resultant external force
		$\vec{f}_i$ = resultant internal force due to interactions with other particles
			$\displaystyle \frac{1}{2}m_iv_{i1}^2+\int_{s_{i1}}^{s_{i2}}(F_i)_tds+\int_{s_{i1}}^{s_{i2}}(f_i)_tds=\frac{1}{2}m_iv_{i2}^2$

We get analogous equations for all the other particles, since work and energy are scalars, we can add them all algebraically
	$\displaystyle \sum_{i}^{}\frac{1}{2}m_iv_{i1}^2+\sum_{i}^{}\int_{s_{i1}}^{s_{i2}}(F_i)_tds+\sum_{i}^{}\int_{s_{i1}}^{s_{i2}}(f_i)_tds=\sum_{i}^{}\frac{1}{2}m_iv_{i2}^2$
	$\displaystyle \sum_{i}^{}T_1+\sum_{i}^{}U_{1-2}=\sum_{i}^{}T_2$
	The initial kinetic energy of the system ($ΣT_1$), plus the word done by all the externa; and internal forces acting on the particles ($ΣU_{1-2}$), equals the final kinetic energy of the system ($ΣT_2$)

Internal forces come in action-reaction pairs
	Since each pair is comprised of vectors of the form $\vec{f}_i, -\vec{f}_i$, action reaction par of forces may travel different paths, in which case the total work done by the force pair is not necessarily 0

Friction caused by sliding
	$μ_kNs= μ_kNs'+μ_kN(s-s')$
	where the first term represents the external work done by the frictional force, while the second term represents the internal work done by the force which primarily ends up as heat in the block

[[PHYS 170 Lecture 30]]