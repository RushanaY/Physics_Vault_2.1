- main idea: 
	- atoms and ions technically have a strict place inside the crystal grid, but it is only a mean value -> they can get shifted form that palce by a small amount and then go back
	- this shift impacts all other atoms around it leading to restoring force -> oscialltion starts 
- this has effect on
	- specific heat -> energy of the oscillation
	- temperatur transport  -> the way the osciallation waves move 
	- thermal expansion - anharmonic potential 
	- acoustic waves 
	- elastic waves 
	- optical effects in IR 
-  mathematical idea: 
	- we have energy $U = U(\vec r)$ 
	- Auslenkung of atoms = change in the electron state - >change in optical, electrical and magnetic properties change 
	- solution to how many oscillations there are is givesn by the hamilton operator $$\hat H = \sum_k \frac{\vec p^2_k}{2M} + \sum_i \frac{p^2_i}{2m} + \sum_{i<j} \frac{e^2}{4 \pi \epsilon_0 | \vec r_i - \vec r_j|} + \sum_{k \leq i} \frac{Z^2 e^2}{4 \pi \epsilon_0 |\vec R_k - \vec R_l|} - \sum+{i,k} \frac{|e^2}{4 \pi \epsilon_0 |\vec r_i - \vec R_k|}$$
# Simpler solution 
- [[Bohr Oppenheimer approximation]]
	-> shifted electrons do not impact the nucleus; shifted nuclei take electrons with them 
- [[harmonic approximation]] 
	-> imagine the atoms being masses and connected by a "spring" 


# ![[Quasiimpuls (crystal momentum)]]

# 3.1. Phonons, dispersion , Zustandsdichte 
# interaction with close neighbrous 
## [[dispersion relation]] 
-> this is the relation of the circular velocity from the [[harmonic approximation]] and the [[Quasiimpuls (crystal momentum)]], which allows to calculate the [[dispersion relation#speed of sound|speed of sound]] 

## [[group velocity]] 
->  how fast energy gets transported (not matter, just energy)
-> is the energy of a wave paket 
$$\nu_G \equiv \frac{d \omega}{d q}$$
In order to look at all atoms and the total picture: 
- In case of our circular frequnency $\omega(q) = 2 \sqrt{\frac{C}{M}} \sin (\frac{qa}{2})$ we get the group velodity as being $\nu_G = \sqrt{C \cdot \frac{a^2}{M}} \cos (\frac{qa}{2})$ 
Looking at the velocity at: 
- In centre of [[brillouin zone]] -> **langwellig** at $q \to 0$ gives $$\nu_G = \sqrt{C \cdot \frac{a^2}{M}}$$ 
- at the edge ov [[brillouin zone]] -> **standing wave** at $q = \frac{\pi}{a}$ gives $$\nu_G =0$$ 
# interaction with neighbhours that are far away 
$$\omega^2 = \frac{4}{M} \sum_p C_p \sin^2 (\frac{pqa}{2})$$
-> it acts in the same way for centre and edge of [[brillouin zone]] as before 


# Oscillation energy
Given:  [[Hamilto operator]] fir harmonic oscillation $$H = \frac{\vec p2}{2m} + \frac{1}{2} m \omega^2 x^2$$
- with eigenvalues $$E_n = \hbar \omega (n + \frac{1}{2})$$
- for N atoms -> 3N independand oscillations 
- boundary conditions: $n=0 (x=0)$ -> $exp(iqNa) = exp(0)=1$ 
	- total energy is all modes summed up $$E = \sum{\vec q r}(n_{\vec qr} + \frac{1}{2}) \hbar \omega+r (\vec q)$$where $r$ is the Dispersionszweig and $q$ is the wave vector 

# [[phonon]] 
= a particle, that is the oscillation of frequency $\omega$ and wave vector $\vec q$ 

The oscillation gets exited into the state $n_{\vec q r}$ = creation of a $n_{\vec q r}$ phonon of type $r$ and wave vector $\vec q$ 
==the higher the oscillation, the more phonons of this type exist== 


## ![[transversal modes]] ## ![[acoustic modes]] 

## [[acoustic branch]] 
we look at the behaviour of the frequency from the [[harmonic approximation#two types of atoms]] in centre and on the edge of the [[brillouin zone]] 
on the edge we get: $$\omega_- (\frac{\pi}{a}) = \sqrt{\frac{2C}{M_1}}$$
	-> it is a solution for the case with only one type of atom 
	- both atoms oscillate bascially with the same amplitude and phase 

# [[optical branch]]
Just like with the [[acoustic branch]] we look at the frequency on the edge of the [[brillouin zone]]: $$\omega_+ (\frac{\pi}{a}) = \sqrt{\frac{2C}{M}}$$
	-> both atoms oscillate out of phase and the Schwerpunkt stays in the same place $$\frac{u_0}{\nu_0} \approx - \frac{M_2}{M_1}$$

![[Kap. 3 grid oscillations 2025-12-21 16.46.21.excalidraw]]



# [[energy band gap]]
-> it is a gap in the [[dispersion relation]], so that there appears an area with oscillation frequencies, that are not possible 
(in 3D [[transversal modes]]s are allowed -> why is that so special?))

If crystal is bade up from ions: 
- optical branch has an oscillation out of phase -> optisch aktiv 
- in multiple atomic basis -> optica modes get created 
- for **p atomic** basis => 3 acoustic branches => ==3p -3== optical branches 

![[Kap. 3 grid oscillations 2025-12-21 16.59.08.excalidraw]]



