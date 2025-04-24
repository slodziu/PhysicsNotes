- Used in [[Boltzmann Distribution]] to [[Normalisation|normalise]] the distribution:
$$Z=\sum_i g_ie^{-E_i/kT},$$
- $g_i$ factor occurs where there are degenerate energy levels

- Can combine partition functions from independent degrees of freedom by multiplying:
$$Z=Z_xZ_yZ_z$$
- To obtain thermodynamic variables using Z:
- [[Internal Energy|Internal energy]]:
$$U=-\frac 1Z\frac{dZ}{d\beta}=-\frac{d\ln Z}{d\beta},\;\;\beta=\frac{1}{kT}$$
- [[Entropy]]:
$$S=\frac UT+k\ln Z$$
- [[Thermodynamic Potentials|Helmholtz free energy]]:
$$F=-kT\ln Z$$

- For continuously varying systems Z given by integral over degrees of freedom (e.g. momentum $E=p^2/2m$):
$$Z=\frac 1A\int_{-\infty}^{\infty}e^{-\beta p^2/2m}dp$$
- Using the [[Density of States|density of states]], the partition function 
$$Z=\int_0^{\infty}D(k)dk=\frac{V}{\lambda_T^3},$$
where $\lambda_T$ is the [[Thermal de Broglie Wavelength]].

## Partition Function of multiple particles
- Partition function of a single atom $Z_1$
- The combined (grand) partition function of a gas for **indistinguishable** particles
$$Z_G\approxeq\frac{Z^N_1}{N!}=\frac{(V/\lambda_T^3)^N}{N!}$$
- For [[Gibbs Distribution]], the grand partition function:
$$Z_G=\sum_ie^{\beta(\mu N_i-E_i)}$$
- Important formula for exams considering derivative of ln:
$$\frac{d\ln{y}}{dx}=\frac{1}{y}\frac{dy}{dx }$$
