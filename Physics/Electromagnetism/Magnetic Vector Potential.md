- Since$\mathbf{\nabla}\cdot\vec B=0$ we know that $\vec B = \mathbf{\nabla} \times \vec A$
- We set $\mathbf{\nabla}\cdot \vec A=0$
- This gives
$$\mathbf{\nabla}^2\vec A=-\mu_0\vec J,$$
where $J$ is the [[Electric Current|current density]].
- This is a [[Poisson's Equation]] in $A$.

We can obtain $\vec A$ from $$\vec A(\vec r)=\frac {\mu_0}{4\pi}\iiint\frac{\vec J(\vec{r'})}{r''}d\tau'$$
and $$\vec A(\vec r)=\frac {\mu_0}{4\pi}\int\frac{I}{r''}dl=\frac {\mu_0}{4\pi}\int\frac{\vec K}{r''}dA'$$
This has boundary conditions:
$\vec B_{above}-\vec B_{below}=\mu_0 (\vec K \times \hat n)$ 
$\vec A_{above}=\vec A_{below}$ 

Magnetic Vector Potential from multiple expansion for a dipole:
$$\vec A_{dip}=\frac{\mu_0}{4\pi}\frac{\vec m \times \hat r}{r^2}$$
where $\vec m$ is the [[Magnetic Dipole Moment]].

Can use the [[Magnetization]] vector to obtain $A$:$$\vec A(\vec r)=\frac {\mu_0}{4\pi}\iiint\frac{\vec M(\vec r') \times \hat {r''}}{{r''}^2}d\tau'$$
- With bound current densities:
$$\vec J_b=\mathbf{\nabla}\times\vec M,\;\vec K=\vec M\times \hat n$$