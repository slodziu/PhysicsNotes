- Can combine [[Functions of the state|state functions]] to make others, but only few are useful:

| Symbol                            | Name                  | Formula     |
| --------------------------------- | --------------------- | ----------- |
| $\def\dbar{{¯\mkern-12mu d}}$ $U$ | [[Internal Energy]]   | $U$         |
| $F$                               | Helmholtz Free Energy | $F = U-TS$  |
| $G$                               | Gibbs Free Energy     | $G=U-TS+pV$ |
| $H$                               | Enthalpy              | $U+pV$      |
- The above apply for systems where the [[Work|work]] term $dW = -pdV$ and there is a fixed number of particles $dN =0$.
- These can be used to relate the partial derivatives to thermodynamic variables
	- e.g. Gibbs Free Energy, using [[Laws of Thermodynamics|first law]]:
		$$G=U-TS+pdV \to dG=Vdp-SdT$$
		 so $G = G(p,T)$, therefore  $dG = (\frac{\partial G}{\partial p})_T\;dp+(\frac{\partial G}{\partial T})_p \;dT$ 
		 can equate the $dp$ and $dT$ terms to obtain $V =(\frac{\partial G}{\partial p})_T$ and $S=-(\frac{\partial G}{\partial T})_p \;dT$.