- At a point $r$ is defined as
$$V(\vec{r})=-\int_O^{\vec{r}}\vec{E}\cdot d\vec{r}$$
- $E$ is the [[Electric Field|electric field]]
- Similarly can be defined at endpoints
$$V(b)-V(a)=\int_a^b \mathbf{\nabla}V\cdot dr$$
- Regions of constant potential are called **equipotential**
- Can be used to reduce vector problems to scalar problems
- Conventionally set zero of the potential at infinity s.t. $V(\infty)=0$.
- Obeys the [[Superposition Principle|superposition principle]] so $V_{tot} = \sum_i V_i$.

- Can define a [[Poisson's Equation]] using $V$:
$$\mathbf{\nabla}^2V=-\frac{\rho}{\epsilon_0}$$
- The value at some point $(x,y)$ is the average around that point:
$$V(x,y)= \frac{1}{2\pi R}\oint Vdr=\frac{1}{4\pi R^2}\oint_{sphere}VdA$$
- Potential due to point charge:
$$V(r)=\frac{1}{4\pi \epsilon_0}\frac{q}{r}$$
- For a [[Continuous Charge Densities|continuous charge distribution]]:
$$V(r)=\frac{1}{4\pi \epsilon_0}\iiint_\tau \frac{\rho(r')}{r}d\tau'$$
