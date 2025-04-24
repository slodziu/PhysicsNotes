- The model assumes the mass of an atom depends on atomic number $Z$ and mass number $A$:
$$M(A,Z) = Zm_p+(A-Z)m_n + Zm_e - BE$$
Where $BE$ is the [[Binding Energy|binding energy]] with equation
$$BE = a_vA - a_sA^{2/3}-a_C\frac{Z^2}{A^{1/2}}-a_A\frac{(A-2Z)^2}{A}-\begin{pmatrix}  1 \\  0 \\ -1   \end{pmatrix}a_PA^{-3/4}$$
where the last term is $\begin{cases} 1, & A,Z \;\text{both even} \\ 0, &A,Z \;\text{both odd}\\ -1, & A,Z \; \text{mixed parity} \end{cases}$ 
This is a quadratic in $Z$, nuclei close to peak stable, and can [[Decay|decay]].
Then one can obtain $\frac{\partial M}{\partial Z}=0$ to get
$$Z=\frac{A}{2+0.0015A^{2/3}}\approx\frac{A}{2}$$
