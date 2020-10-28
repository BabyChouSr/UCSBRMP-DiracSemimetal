# UCSBRMP Effect of Inversion Asymmetry on Quantum Confinement of Dirac Semimtal Cd3As2
In this project, I studied the effects of inversion asymmetry on the electronic transport of the quantum system. I modeled the Dirac Hamiltonian equation of the system and then created simulations by changing the values of inversion asymmetry and hybridization. 
I created a Landau Level detector where the user can input experimental data and the output helps instantly detect the Landau levels of the system.
I also created a program that calculates the spectral density of a system

## Effect of Inversion Asymmetry on E vs. B and E vs. K
Created using the Dirac Hamiltonian equation:
```math
\mathcal{H} = \hbar v_f \begin{pmatrix} (k_x\sigma_y - k_y\sigma_x) & 0  \\ 0 & - (k_x\sigma_y - k_y\sigma_x)\end{pmatrix} \\[2mm] \hspace*{15mm}+ \begin{pmatrix} \Delta_i & 0  \\ 0 & - \Delta_i\end{pmatrix} \\[2mm] \hspace*{15mm} + \begin{pmatrix} 0 & \Delta_h  \\ \Delta_h & 0 \end{pmatrix} \\[2mm] \hspace*{15mm} + \begin{pmatrix} g^* \mu_B B_0 \sigma_z & 0  \\ 0 & g^* \mu_B B_0 \sigma_z \end{pmatrix}
```
