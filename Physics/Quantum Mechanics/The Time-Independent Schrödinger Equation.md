- Applying [[Separation of variables]] on the [[Schrödinger equation]] and looking at the position terms yields:
$$-\frac{\hbar^2}{2M}\frac{d^2u(x)}{d x^2} + V(x)u(x) = Eu(x)\tag1$$
- To see how the separable solutions of the form evolve in time:$$\psi(x,t) = Ae^{-iE_nt/\hbar}u(x)\tag2$$
are known as **stationary states** as things like [[Momentum|Momentum]] and [[Energy|energy]] are constant in time for such solutions, these correspond to momentum $p=\hbar k$, energy $E_n = \hbar^2\pi^2n^2/2Ma^2$.
- Can form solutions by superposing these stationary states: $$\psi(x,t) = \frac{1}{\sqrt{2\pi}}\int_{-\infty}^\infty c(k)e^{-i\hbar k^2t/2M}e^{ikx}dx,\tag3$$
$$c(k)= \frac{1}{\sqrt{2\pi}}\int_{-\infty}^\infty \psi(x,0)e^{-ikx}dx\tag4$$
Where $c$ is the [[Energy Probability Amplitude|energy probability amplitude]].
- Can be described as an [[Eigenvalue|eigenvalue]] equation, using the [[Hamiltonian Operator|Hamiltonian operator]]:
$$\hat{H}u(x)=E\;u(x)\tag5$$
- This shows that stationary states have **definite energy**.
- Applying the [[Superposition Principle|superposition principle]], one can see how the wavefunction evolves in time:
$$\psi(x,t)=\sum_{n=1}^\infty c_n(t)u_n(x), \tag6$$
$$c_n(t)=c_n(0)e^{-iE_nt/\hbar} \tag7$$
