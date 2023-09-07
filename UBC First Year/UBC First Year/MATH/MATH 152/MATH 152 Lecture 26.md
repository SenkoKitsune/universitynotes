The angle θ is known as the argument of $z$

$\displaystyle z\cdot\overline{z}=(a+bi)(a-bi)=a^2-b^2i^2 = a^2+b^2 =  |z|^2$

Fundamental theorem of algebra
	Every complex polynomial of degree $d>0$ has $d$ complex roots
		(counted with multiplicity)

Suppose $p(x) = a_nX^n + a_{n-1}X^{n-1} + ... + a_1x+a_0$ where all coefficients $a_n, a_{n-1}, ... , a_1, a_0$ are real numbers
	If $z$ is a root, so is $\overline{z}$
	$\overline{z+w}=\overline{z}+\overline{w}$
	$\overline{z\cdot w} = \overline{z}\cdot\overline{w}$
	$\displaystyle \overline{\frac{z}{w}}=\frac{\overline{z}}{\overline{w}}$
	$\displaystyle P(z) = 0 \leftrightarrow a_nZ^n + a_{n-1}Z^{n-1}+ ... + a_1Z + a_0 = 0$
		$\displaystyle =\overline{a_n}\overline{Z^n}+\overline{a_{n-1}}\overline{Z^{n-1}}+...+\overline{a_1}\overline{Z} + \overline{a_0} = 0$
		$=a_n|\overline{Z}|^n+a_{n-1}|\overline{Z^{n-1}}| + ... + a_1|\overline{Z}| + a_0 = 0$
		$P(z) = 0 \to \overline{z}$ is also a root

The exponential
	$e^{a+bi} = e^a(cos(b)+isin(b))$

Polar form 
	$z = a+ib$
		can find r and θ so that
			$a = r\cos(θ), b = r\sin(θ)$
			$z = r\cos(θ)+r\sin(θ)i = r (\cosθ + \sinθi)$
				$= re^{θi}$
				where $r = |z|$
			Geometrically this is written as a vector as its length times direction

Geometric interpretation of multiplication using polar form
	$z_1 = r_1e^{iθ_1}$
	$z_2 = r_2e^{iθ_2}$
	$z_1z_2 = (r_1r_2)e^{i(θ_1+θ_2)}$
	$(z_1,z_2)$ has magnitude $r_1r_2 = |z_1||z_2|$ 
		argument/angle for $z_1z_2$ is the sum of angles

[[MATH 152 Lecture 27]]