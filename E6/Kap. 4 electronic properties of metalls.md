# 4.1 [[free electron gas]] 
- localised electtrins 
	- in crystals 
	- good isolators 
- delocolised electrons 
	- in metalls 
	- electrons do not interact with atomic cores and not with eachother 
		- => [[free electrons]] gas 



## 4.1.1. [[Drude Sommerfeld model]] 
==classical explanaition for conductivity== 
=>  where suddently the ideas: 
	- [[Pauli exclustion principle]] 
	- [[Fermi dirac distribution]] 
	become improtant are the innovative part 
- we have calculated the [[dispersion relation for electrons]]
$$E(\vec k) = \frac{\hbar^2 k^2}{2m}$$
## [[dispersion relation]] 
-> [[dispersion relation for electrons]]


### [[density of states (Zustandsdichte)]] 

==number of states per energy unit== (also analogous to what a [[phonon]] does) 
- assume a cubic body!
- k value is $\vec k_{x,y,z} = \frac{ 2n \pi}{L_x,y,z}$ 
	- => 3D density of states $D(\vec k) = 2 \frac{V}{8 \pi^3}$ 
		- => energy of an electron per square $$E(\vec k) = \frac{\hbar^2 k^2}{2m}$$
- ![[electronic properties of metalls 2025-12-25 13.32.02.excalidraw]]

###  [[fermi energy]] 
- [[Pauli exclustion principle]] says that only 2 electrons with different spins can have the same eigen state 
- maximal possible energy when filling up the system is the fermi energy $E_F$ 
- $T=0$ gives a sphere with radius $k_F$ being the [[fermi sphere]], whose surface is [[fermi surface]] -> seperates filled from unfilled states 
- using the [[fermi wave number]] 
- there are also [[fermi velocity]], [[fermi wavelength]], [[fermi wave number]] and much more 


### [[fermi sphere]]
- at $T=0$ we have a sphere in the $\vec k$ space with the radius $k_F$ 
- ==it has all the filled states==


### [[fermi surface]] 
- it is the surface of the [[fermi sphere]]


### [[fermi wave number]]

Number of filled states:
$$N = 2 (\frac{V}{(2\pi)^3}) \cdot (\frac{4}{3} \pi k_F^3)$$
	$2 (\frac{V}{(2\pi)^3})$ :  [[density of states (Zustandsdichte)]] in the k space 
	$(\frac{4}{3} \pi k_F^3)$ :  volume of the k space 
=> we get the wave number $$k_{F, 3D} = (3 \pi^2 n_{3D})^{1/3}$$
# typical values 
For the electronic density of $n \approx 5 \cdot 10^{22}cm^{-3}$ we have the according values:
- fermi wave number $$k_F \simeq 10^8 cm^{-1}$$
- [[fermi energy]]$$E_F = \frac{\hbar k_F^2}{2m} \simeq 4 eV$$
- [[fermi temperature]] $$T_F = \frac{E_F}{k_F} \simeq 50 \space 000K$$
- [[fermi wavelength]] $$\lambda_F = \frac{2 \pi}{k_F} \simeq 1 \overset{\circ}{A}$$
- [[fermi velocity]] $$\nu_F = \frac{p_F}{m} = \frac{\hbar k_F}{m} \simeq 10^8 cm/s$$


## 4.1.2. [[fermi gas]]
- for $T>0$ we get the [[Fermi dirac distribution]] being $$
 f_{FD} (E) = \frac{1}{e^{\frac{E- \mu}{k_B T}}+1}$$
with $\mu$ being the [[chemical potential]]	

==It is the probability that a state is filled==

$T=0K$
- all states under $E= \mu = E_F$ are filled 
- all states above are empty
$T>0K$ 
- electrons can be thermally exicted 
- those exited electrons leave the states with $E<E_F$ and go to states  with $E>E_F$
-> higher temperature means more electrons go on this journey and he calls it the "Umwandlung" 

Umwandlung:
- happens in the area of a around $k_B T$
- at toom temperature the percentage of electrons, that do the Umwandlung is: $$\frac{k_B T}{E_F} \approx 10^{-2} = 1\%$$
- [[heat capacity]] is in this case 
$$C_P = \gamma \cdot T + A \cdot T^3$$
	- the closest that experimental values are to the theoretical ones is in case of the alkali metals 
	- for transition metalls the assumtion of [[free electrons]] does not hols, because the d-orbit has too much influence onto the [[density of states (Zustandsdichte)]]
	- generally the expected values are not really what is measured -> reason is the fact that we did not consider all the other possible interactions (like elektron with crystal potential, electron with phonons, electron with eachother) -> the effective mass is therefore bigger -> has influence on the [[Beweglichkeit (mobility)]] 


## electron density
# ![[electron density]] 
## 4.1.3. [[heat capacity]] 
- it is caused by both [[phonon]]s and electrons 
$$C_V^{classical} = \frac{\partial \langle U \rangle}{\partial T}|_V = 2 \cdot N \cdot 3 \cdot \frac{1}{2} k_B = 3 N k_B$$
## [[specific heat capacity]] 
$$c_v = \gamma \cdot T$$
with the [[Sommerfeld coefficient]] $$\gamma = \frac{\pi^2}{2} = \frac{n k_B}{T_F}$$
The reason why it is so different to the heat capacity on its own is again Pauli principle. For the most electrons part of their degrees of freedom are "forzen", unusable because the space is already taken up by someone else. 

# 4.2. Transporteigenschaften 

## 4.2.1.  [[electric conductivity]]
- Calculated with $$\sigma_{el} = \frac{J_{el}}{E} = n e \mu$$
	- temperature dependance 
		- observed: $\rho = \sigma^{-1}$ 
		- from the quation we see that the mean distance between collistions is temperature dependand 
		- in metalls scattering throuhg: phonones, defects, Probenoberfläche  
		- scattering time is the sum of all $\tau^{-1}$ 
- denoted with $\sigma_{el}$ is the proportionality constant between the [[Electric Force]] and [[current density]] $$\vec J_{el} = \sigma_{el} \vec E = - \sigma \cdot \triangledown \phi_{el}$$
	-  use the [[drude mean velocity]] and [[electron density]] $n$ $$\vec J_{el} = - e n \vec \nu_D = n e \mu \vec E$$

- [[thermal conductivity]] $$\vec J_h = - \kappa \cdot \triangledown T$$
##  temperature dependance of the conductivity and resistance 

General relation from experimets is:  $$\rho = \sigma^{-1}$$
from the equation : $$\rho^{-1}_{el} = \sigma_{el} = \frac{ne^2 l}{m \nu_F} = \frac{ne^2 \tau}{m}$$
	we see that only $l$, or better so $\tau$ are temperature dependant
	-> in metalls scattering is usually from 
		- phonons
		- defecs 
		- surface of the object 
		=> scatterin time is therefore from the [[Mattheissen rule]] $$\tau^{-1} = \tau^{-1}_{phonon} + \tau^{-1}_{defect}...$$
		this allows to look at all scattering parts seperately

### [[electron phonon scattering]]

### [[electron defect scattering]] 

# experimentally
- the scattering changes the conductivity a lot and has to be considerd, because there are no pure enough crystals that wouldn't at least have the scatterin on defects -> leads to [[Restwiderstand (residual resistance)]] 
-> we need the [[residual resistans ratio (restwiderstandsverhältnis)]] $$RRR = \frac{\rho(300K)}{\rho_0}$$

### 4.2.2.  [[thermal conductivity]]
Definition:
$$\vec J_h = - \kappa \cdot \triangledown T$$
Comparing with [[electric conductivity]] we get the [[Wiedermann Franz law]] $$\frac{\kappa}{\sigma_{el}} = \frac{\pi^2}{3} (\frac{k_B}{e})^2 T$$
-> this makes sense, because in metalls both electric and thermal are important

The ration of those two in metalls is the proportionality number [[Lorenz number]] $$L = \frac{\pi^2}{3} (\frac{k_B}{e})^2 \equiv \frac{\kappa}{\sigma \cdot T} = 2.44 \cdot 10^{-8} W \Omega/K^2$$
# temperature dependance 
- there is a maximum of thermal conductivity
- the maximum is better visible in low temperature, but the material has to be clear 
- in alloys there is no maximum (to "dirty")


## 4.2.3. mobility in magnetic fields 
-> in [[electric conductivity]] electrons move because of a nelectric field 
taking the part of the frequency we get the [[cyclotron velocity]] $$\omega_c \equiv \frac{e}{m} B$$
Actuallty this effect is nicely sumed up in the:
# [[Hall effect]]
![[thermal conductivity 2025-12-29 17.09.40.excalidraw]]

Describtion:
- we have an E field along a conductor and the whole thing is inside a B field, orthogonally 

 -> from the measurement of the [[Hall constant]] we can get the algebraic sign (Vorzeichen) of the charge carrier in the solid body 


------------ 

==Modells for calculating electic transport:==  

# [[Drude modell]]
- ==classical==
- assumption: **electrons move with mean velosity** $\nu_{th}$ 
- accelerated with the el field $\vec E$, collide with atomic core => lose velocity because of friction 
- [[drude mean velocity]]$$\vec \nu_D = - \frac{e \tau}{m} \cdot \vec E = - \mu \cdot \vec E$$
	$\tau$ - characteristic collistion time (probably the amount of time the collistion takes)
	$\mu= \frac{e \tau}{m}$ - [[Beweglichkeit (mobility)]]   





# [[Sommerfeld model]] 
- assume -> electrons are in  [[fermi gas]], that can have the [[Schroedinger equation]] and [[Pauli exclustion principle]] applied to 
- for the current flow we need the density "before" and "after": $$\vec J_{el} = - \frac{en \hbar}{m} \delta \vec k$$
	- this is achievable if there is the **change of momentum ov the wave vector** -> possible  through external force and scattering 
		- scattering also takes into account the relaxation time $\tau$ , like in the [[Drude modell]] $$\frac{\partial \langle \vec k \rangle }{\partial t}|_{scatter} = - \frac{\delta \vec k}{\tau}$$
	- change of the force is from the [[equation of motion]] $$\vec F = - \vec E = m \frac{\partial \langle \vec \nu \rangle}{\partial t} = \hbar \frac{\partial \langle \vec k \rangle }{\partial t}$$$$ \to \frac{\partial \langle \vec k \rangle }{\partial t}|_{force} = - \frac{e \vec E}{\hbar}$$
	- integrated over the whole change in force we get the change in **momentum** $$\int \frac{\partial \langle \vec k \rangle }{\partial t}|_{force} dt = \langle \vec k \rangle (t) - \langle \vec k \rangle^0 = \delta \vec k = - \frac{ e \vec E t}{\hbar}$$
		- in the time $t$ the momentum of the electron gets bigger because of the force $\vec F$ by the amount of $\hbar \partial \vec k$
		- ==this is the same, as the **shift of the [[fermi sphere]]** by the factor $\partial \vec k$ in the time $t$== 
		- The [[fermi surface]] can show the allowe and not allowed states 
[[fermi surface 2025-12-29 16.00.47.excalidraw]]

# 4.3  [[energy band]] 
- expansion of the free electron gas theory, by putting the electron in the potention of the nuclei and other electrons 
-> it leads to a complicated [[Schroedinger equation]], reminding of the [[pertubation theory]] from quantum mechanics 

In order to solve it there are two ways to look at the problem, which go from the opposite sides, but end up in the same place: 

### 4.3.1.  [[quasi free electron]] 
- assume electrons are free to move, therefore the potential of the nulceus and other electrons is assumed to be a non important pertubation -> $V(\vec r) =0$ 
- a good approximation for [[delocolised electron]]s 

### 4.3.2. Tight binding modell 
## [[quasi bound electron]] 
- start at localised electrons 
- [[Tight binding method]]: interaction of electrons between neighbouring atoms new orbitals get created -> those can be described though a linear combnation of teh atomic orbitals 

==both of the approximations of quasi free and quasi bound electrons end up showing the existance of the [[energy band]]s and [[energy band gap]]s== 

ANother thing that becomes relevant in all those apporximations, is the [[effective mass]], which comes from the dispersion relation: $$m^* = \frac{\hbar^2}{2 \beta^i a^2}$$






# 4.4 Metalls, semicinductors, isloators 
# Definitions of metal, semi conductor and half metal
 we need for the definition ->  [[energy band gap]] (because the atoms are so close to eachother)
- the filling of those bands at $T=0K$ is just like in [[fermi gas]]  -> the states get filled from the bottom and all electrons get a place 

with $E_G$ we mean the energy of the gap! 
## [[metall]]
- states arae empty inside the energy gap
- current flows if an electric field applied 

## [[semiconductor]]
- $E_g \leq 4eV$ -> current flow at $T=0K$ and no current at $T>0$ 

## [[isolator]] 
-> when $$E_g >= 4 eV$$
-> for $T>0$ there is no current possible 


In the middle (at 3 or 4 eV) the conductivity is very much temperature dependant 

## [[Halbmetall]] 
-> here what happens is a small **overlapp** of the [[energy band gap]]s 
- overlapp small, [[density of states (Zustandsdichte)]] very small => small number of current carrierers
- nevertheless there is still current flow at $T=0K$ 
-  another effect of the overlapp -> different [[dispersion relation]] in different directions of the crystal 



==crystals are halbmetalle==


## 4.4.1.  number of states in the band
-> helps to determine if a **crystal** is an isolator or a metall

- in case of [[quasi free electron]]s :
	- 
## 4.4.2 band structure, state density 



# 4.5 Fermi surfaces of metals 
## 4.5.1.  [[free electrons]] 
change in temperature, specifically the increase changes the way the states are filled, but only in the neighborhood of the [[fermi surface]]
in case of free electrons the fermi surface is a cicle 
the [[electron density]] from that coems from the [[fermi energy]] gives then the [[fermi wave number]] in 2D is then $$k_F = \sqrt{2 \pi n_{2D}}$$
- fermi radius is dependand on the electrondensity and the number of valenz electrons 
- this leads to big differences between fermi surfaces 
- in case of small electron densities - >fermi wave vector is also small (wow, logical)
- the fermi circe (the fermi surface) is completely **inside** of the first [[brillouin zone]] => just as we expect from free electron gas 
- if the fermi wave number is bigger -> fermi surface outside of the first brillouin zone 
	- 1BZ barely filled 
	- 2BZ partly filled, looks like ovals in the periodic scheme 
	- 3BZ is empty 
- more overfilling of the zones leads to the 3BZ having "spikes" and the 2BZ to hve "holes" => this can be easily shown by drawing onw zone and making it periodic 

## 4.5.2. almost free electrons 
almost free electrons
- there are energy band gaps on the borders of the BZ 
- schroedinger equation at the borders of the zone is solved by standing zones 
	- gradients of $E(\vec k)$ are parallel to the BZ border 
	- the lines of constant energy $E (\vec k)$ are prependicular to the BZ 

- important
	- crystal potential rounds to corners of the BZ 
	- the total volume that is inside of the fermi surface is dependand on the number of electrons => has to stay the same 

- what is it in metalls?
	- alkaline: in bcc structure -> fermi surface is very much inside the first BZ  and is shaped like a sphere 
	- edelmetall: also inside the first BZ, but the borders get touched and the sphere doesn't look as perfect 

## 4.5.3. electrons in magnetic fields, electron and hole orbits , measurement of fermi surfaces 
Experimentsl determination of the shape pf the fermi surfe 
- electron move orthogonal to the magnetic field and the enregy gradient 
- for movement ew need free electron states => lokated at the boundaries of the surface 
- depending on the f surface the electrons might behave like gaps in magnetiv fields 
- almost empty bands -> orbits look like made from the electrons 
- almost filled bands -> gap orbits 
- differenc in orbits between:
	- open orbit -> get continued in the periodic zone scheme 
	- metalls might have both types 
- a metall can be exited along one direction of the zone and this leads to oscillation in certain periods and certain directions too
- basically exiting the metall in acertain direction will show what kind of fermi surface it 

# 4.6 Electrons and gaps 
we go back to the idea of [[effective mass]] and especially the strange  idea of it being negative 

-> happens if we don;t use the modell with free electrons 

- effective mass is give though the curvature of the band at the place of $k_0$ 
- looking at this place closer , it shows the relation if acceleration and force as being $$\vec a \sim - \vec F$$
- this way we get the negative mass 
- but instead of having this bad consept we can switch the Vorzeichen -> we get a particle , with positive mass, that is the we call a **gap** , which moves in the opposite direction 

- a gap is a quasi particle 
	- behaves just like a particle, but is not one. we need it so we don't have to suffer with negative mass 
	- wave vector 
		- full band has $\sum \vec k =0$ -> if we take one electron out we get the negative wave vector $- \vec k_e$ 
	- energy
		- same idea -> negative energy 
		- in free states the particles go in the dispersion relation 
			- electrons go down
			- gaps go up 
	- effective mass
		- negative mass possible 
	- velocity
		- $\vec \nu_h (\vec k) = \vec \nu_e (\vec k)$
	- equation of motion 
		- gaps move like paricles with postivie charge (bascially negaitve mass)



