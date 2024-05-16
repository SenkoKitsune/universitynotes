PV from an atomistic point of view\
  Number density: $n \equiv \dfrac{N}{V}$ for $N$ particles in volume $V$
  $v_x$: x-component of the velocity
  Velocity distribution of number density: $n_v(v_x)dv_x\equiv \dfrac{Nv_x}{V}$ where $Nv_x$ is the number of particles with $v_x \in \set{v_x, v_x + dv_x}$
  Notice that the number density is just the intergral of $n_v$ over all $v_x$
    $\displaystyle n = \dfrac{N}{V} = \int_{-\infty}^{\infty}n_v(v_x)dv_x$

$v_xdt$ is the distance that particles with x-componenet of velocity $v_x$ move in $dt$
$A$ is the corss-sectional area of the piston
All of the particles within volume $Av_xdt$ for whome $v_x \in \set{v_x + dv_x}$ will hit the piston in a time $dt$
So the number of molecules with $v_x \in \set{v_x, v_x + dv_x}$ that hit the piston in time $dt$ is:
  $n_v(v_x)dv_xAv_xdt$

The total momentum of those moleulces:
  $mv_xn_v(v_x)dv_xAv_xdt = mv_x^2n_v(v_x)dv_xAdt$
  where m is the mass of each molecule

So the momentum change of the moleules is
  $dp = 2mv^2_xn_v(v_x)dv_xA$
Considering all x-velocities, the force on the piston will be
  $F = \int_{0}^{\infty}2mv_x^2An_v(v_x)dv_x$

Average of $v_x$ over the distribution will be 
  $\displaystyle \langle v_x \rangle = \dfrac{\int_{0}^{\infty}n_v(v_x)v_xdv_x}{\int_{0}^{\infty}n_v(v_x)dv_x}$
  and the average of $v_x^2$ over the distribution will be
    $\displaystyle \langle v^2_x\rangle = \dfrac{\int_{-\infty}^{\infty}n_v(v_x)v_x^2dv_x}{\int_{-\infty}^{\infty}n_v(v_x)dv_x} = \dfrac{\int_{-\infty}^{\infty}n_v(v_x)v_x^2dv_x}{\dfrac{N}{V}}$
    And therefore
      $\displaystyle \int_{0}^{\infty}n_v(v_x)v_x^2dv_x=\dfrac{N}{2V}\langle v_x^2\rangle$

Putting these together we have 
  $\displaystyle \int_{0}^{\infty} 2mv^2_xAn_v(v_x)dv_x 2mA \int_{0}^{\infty}n_v(v_x)v^2_xdv_x = 2mA\frac{N}{2V}\langle v^2_x\rangle$

So $PV = Nk_bT$ and $PV = N\dfrac{2}{3}\langle KE\rangle$, establising a relation between $k_bT$ and $\langle KE \rangle$ for an ideal gas




Microscopic calculation: $PV = Nm\langle v_x^2\rangle = \dfrac{N}{3} m\langle v^2\rangle$
Experimental observation $PV = Nk_bT$

Together, these imply:
  $3k_bT = m\langle v^2\rangle \to \dfrac{3}{2}k_bT = \langle KE\rangle$ where $\langle KE \rangle$ is the average kinetic energy per particle
  $\dfrac{1}{2}k_bT = \dfrac{1}{2}m\langle v_x^2\rangle = \dfrac{1}{2}m\langle v^2_y\rangle = ...$


For an ideal gas, U is whell define: KE are the only avaliable degrees of freedom, so for a system with N particles, $U = \sum_{N} KE$

But $U = \sum_N KE = N \cdot \langle KE \rangle = \dfrac{N}{2}m\langle v^2\rangle = \dfrac{3}{2}Nk_bT = \dfrac{3}{2}PV$ for a monatomic ideal gas only

Notice $U$ only depend on temeprature for an ideal gas

$\Delta U = Q + W$
  $Q$ is energy added as heat
  $W$ is energy added in some other form


Quasistatic:
  - Is the system in equilibrium with itself?
  - If you did the process marginally slower or faster would the result be the same
  - For a gas, this typically means parts move much slower than the speed of sound

Isothermal
  - T of system remains constant
  - Does NOT specify anything about heat in or out

Adiabatic
  - No heat in or out
  - For quasistatic processes, this implies no entropy change, $dS = 0$
  - In practice, this often means "fast" processes, fast enough that heat cannot low in or out since it's impossible to insulate perfectly
      Not fast enough that the system becomes not quasistatic
