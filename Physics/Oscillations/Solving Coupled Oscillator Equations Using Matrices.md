Considering a system of two mases $n=2$ from [[Coupled Oscillators|coupled oscillator]] example, can rewrite coupled equations as matrices:
$$\begin{pmatrix}  
m_1 & 0 \\  
0 & m_2 
\end{pmatrix} \frac{d^2}{dt^2}\vec{x}(t) = - \begin{pmatrix}  
k_1+k_{12} & -k_{12} \\  
-k_{12} & k_2+k_{12} 
\end{pmatrix}\vec{x}(t) \tag{1},$$ where $\vec{x}(t) = \begin{pmatrix}  x_1(t) \\  x_2(t)   \end{pmatrix}$ . Then set $M = \begin{pmatrix}  m_1 & 0 \\  0 & m_2 \end{pmatrix}$, $K = \begin{pmatrix}  k_1+k_{12} & -k_{12} \\  -k_{12} & k_2+k_{12} \end{pmatrix}$ 
So $$\frac{d^2}{dt^2}\vec{x}(t) = -(M^{-1}K)\;\vec{x}(t) \tag{2}$$

Assume a normal mode $\vec{x}_n(t) = cos(\omega t)\begin{pmatrix}  a \\  b   \end{pmatrix}$ , let $D = M^{-1}K$
$$-\omega^2\vec{x}(t)= -D\vec{x}(t) \tag{3}.$$
This is an [[Eigenvalue|eigenvalue]] equation such that:
$$DA = \omega^2A \;\text{if}\; A=\begin{pmatrix}  a \\  b   \end{pmatrix} \tag4$$
Finding solution by $$det(D-\omega^2I) = 0 \tag5$$ to obtain $\omega^2_{+}$ and $\omega^2_{-}$ . Then substitute into equation 4 to obtain $\frac{b}{a}$ or $\frac{a}{b}$ ratio to get $A_+$ and $A_-$ . Finally full solution:
$$\vec{x}(t) = \alpha_+cos(\omega_+t +\theta_+) + \alpha_-cos(\omega_-t+\theta_-). \tag6$$
Where $\alpha_\pm$ and $\theta_\pm$ from initial conditions.