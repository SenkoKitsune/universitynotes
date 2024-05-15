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
