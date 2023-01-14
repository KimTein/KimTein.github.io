---
title           : "[Raman] Basic Theory"
excerpt         : "Baisc Theory of Raman Spectroscopy"
author          : KimTein
author_profile  : true

toc             : true 
toc_sticky      : true
sidebar_main    : true
date            : 2023-01-08 #posing date
last_modified_at: 2023-01-10 12:00:00 +0900

categories:
  - raman
tags: 
  - Raman # Write tag no ""

published: true

---
<!-- outline-start -->
<br>

# Energy Units and Molecular Spectra
{: .text-center}
___
## Plane Polarized electromagetic radiation
<br>
<center>
<a href='https://en.wikipedia.org/wiki/Plane_of_polarization'>
<img alt="plane polarization" src="https://upload.wikimedia.org/wikipedia/commons/9/99/EM-Wave.gif" width=400>
</a>
</center>
___
<figcaption style="text-align: center;">
[Figure. 1] Plane of Polarization </figcaption>

<br>
&nbsp; [Figure. 1] illustrates a wave of polarized electromagnetic radiation traveling in the x-direction. The electric component is y-direction and magnetic is z-direction.
<br>
&nbsp; Hereafter, we consider only the former. (Don't involve magnetic phenomena). The electric field strength (_E_) at a given time (_t_) is expressed by 

$$ E = E_0cos2\pi \nu t \tag{1} $$

$$E_0$$ is the amplitude, $$\nu$$ is the frequency of radiation.

<br>
&nbsp; The distance between two points of the same phase in successive waves is called the _"wavelength"_ , $$\lambda$$, which us measured in units.($$\mathring{A}$$(angstrom), $$nm$$(nanometer), $$m\mu$$(millimicron), and $$cm$$(centimeter)). The relationships between them are:

$$1 \mathring{A} = 10^{-8} cm = 10^{-1} nm = 10^{-1} m\mu  \tag{2} $$

## Frequency

&nbsp; The frequency, $$\nu$$ is the number of waves in the distance light travels in one second. Thus, 

$$ \nu = \frac{c}{\lambda} \tag{3} $$

$$c$$ is the velocity of light $$(3 \times 10^{10} cm/s) $$. And if $$ \lambda $$ is in the unit of centimeters, its dimension is $$ (cm/s)/(cm) = 1/s $$. This "reciporal second" unit is also called the "hertz" $$(Hz)$$.
&nbsp; There's another parameter is the _"wavenumber"_, $$\tilde{\nu}$$ defined by

$$ \tilde{\nu} = \frac{\nu}{c} \tag{4} $$

&nbsp; The difference between $$\nu$$ and $$ \tilde{\nu} $$ is obvious. It has the dimension of $$ (1/s)/(cm/s) = 1/cm.$$ By combining Eq.(3),Eq.(4) we have

$$ \tilde{\nu} = \frac{\nu}{c} = \frac{1}{\lambda}(cm^{-1}) \tag{5} $$

&nbsp; Also, we can express by $$v$$

$$ \nu = \frac{c}{\lambda} = c \tilde{\nu} \tag{6} $$

&nbsp; As shown earlier, the wavenumber$$(\tilde{\nu})$$ and frequency $$(\nu)$$ are different parameters, yet these two terms are often used interchangeably. Thus, we can express by **IR** and **Raman spectrosopists** such as "frequency shift of $$10 \;cm^{-1}$$". 
## Interacts with an electromagetic field
&nbsp; We can know a transfer energy from the field to the molecule and it can occur only when Bohr's frequency condition is satisfied.(If a molecule interacts with an electromagetic field). 

$$ \Delta E = h\nu = h\frac{c}{\lambda} = hc\tilde{\nu} \tag{7} $$

&nbsp; Here $$h$$ is Planck's constant $$(6.62 \times 10^{-27}erg\; s)$$ and $$ \Delta E $$ is the difference in energy between two quantized states. Thus, $$ \tilde{v} $$ is directly proportional to the energy of transition. 

&nbsp; Let's Suppose that

$$ \Delta E = E_2 - E_1 \tag{8} $$

$$ E_2 $$ : Energy of the exicted states, $$ E_1$$ : Energy of the gound states.

&nbsp; Then, the molecule _absorbs_ $$ \Delta E $$ when it is exited from $$ E_1 $$ to $$ E_2$$ ( $$E_1 \rightarrow E_2 $$ ) and _emits_ $$ \Delta E $$  when it reverts from $$ E_2 $$ to $$ E_1 $$ ( $$ E_2 \rightarrow E_1 $$ ).

&nbsp; We can express $$ \Delta E $$ in terms of various energy units. Thus, $$ 1 cm^{-1} $$ is :

$$ \begin{align} \Delta E &= E^2 - E^1 = hc\tilde{\nu} \\ &=[6.62 \times 10^{-27} (erg \; s)][3 \times 10^{10} (cm/s)][1(1/cm)] \\&= 1.99 \times 10^{-16} &\; (erg/molecule) \\ &= 1.99 \times 10^{-23} &\; (joule/molecule)\\ &= 2.86 &\; (cal/mole) \\ &=1.24 \times 10^{-4} &\; (eV/molecule) \end{align} $$

## Observed Region

&nbsp; We mainly concern with vibrational transitions which are observed in infrared(**IR**) or **Raman Spectra**. They appear in the $$10^{-4} \sim 10^2 \; (cm^{-1}) \; $$ region and originate from vibrations of nuclei constituting the molecule. Raman spectra are related to electronic transitions. Thus, it is important to know the **relationship between electronic and vibrational states**.
<br>
<center>
<a href='https://www.researchgate.net/figure/Overview-of-various-imaging-modalities-within-the-electromagnetic-spectrum_fig1_320505957'>
<img alt="electromagnetic spectrum" src="https://www.researchgate.net/profile/Rekha-Gautam/publication/320505957/figure/fig1/AS:551293086965760@1508449922411/Overview-of-various-imaging-modalities-within-the-electromagnetic-spectrum.png" width = 600>
</a>
</center>
___
<figcaption style="text-align: center;">
[Figure. 2] Electromagnetic Spectrum </figcaption>
<br>
&nbsp; Furthermore, vibrational spectra of small molecules in the gaseous state exhibit rotational fine structures. Thus, it's also important to know the relationship between **vibrational and rotational states.** [Figure. 3]
<br>
<center>
<a href='https://www.researchgate.net/figure/Schematic-representation-of-various-energy-levels-of-a-diatomic-molecule-An-absorption_fig5_239968471'>
<img alt="Energy levels of a diatomic molecule" src="https://www.researchgate.net/profile/Charles-Geiger/publication/239968471/figure/fig5/AS:341802461745158@1458503465601/Schematic-representation-of-various-energy-levels-of-a-diatomic-molecule-An-absorption.png" width = 500>
</a>
</center>
___
<figcaption style="text-align: center;">
[Figure. 3] Energy leves of a diatomic molecule </figcaption>
<br>

# Vibration of a Diatomic Molecule
{: .text-center}

## Classical treatment

&nbsp; Consider the vibartion of a diatomic molucule in which two atoms are connected by a chemical bond.[Figure. 4]

<center>
<img alt="Energy levels of a diatomic molecule" src="/assets/images/posts/raman/two_atoms.png" width = 500>
</center>
___
<figcaption style="text-align: center;">
[Figure. 4] Two atoms connected by a chemical bond </figcaption>
<br>
&nbsp; Each masses of atom 1 and 2 are $$m_1$$ and $$m_2$$ and $$r_1$$ and $$r_2$$ are the distances from the center of gravity (C.G.) to the atoms designated. Thus, $$r_1 + r_2 $$ is the equilibrium distance. Then, the conservation requires the ralationships:

$$ \begin{align} m_1r_1 &= m_2r_2 \tag{9} \\ m_1(r_1 + x_1) &= m_2(r_2 + x_2) \tag{10} \end{align} $$

&nbsp; Eq.9 and Eq.10 combine

$$ x_1 = \Big(\frac{m_2}{m_1}\Big)x_2 \quad \text{or} \quad  x_2=\Big(\frac{m_1}{m_2}\Big)x_1 \tag{11} $$

&nbsp; In the classical treatment, we can regard the chemical bond as a spring. It obeys the Hooke's law, so we can express the restoring force, $$f$$ :

$$f = -K(x_1 + x_2) \tag{12} $$

&nbsp; Where K is the force constant, and the directions of the force are opposite to each other. Now, combining the Eq.11 and Eq.12, we obtain :

$$ f = -K \Big(\frac{m_1 + m_2}{m_1}\Big) = -K \Big(\frac{m_1 + m_2}{m_2}\Big) \tag {13} $$

&nbsp; Using Newton's equation of motion, we obtain for each atom as :

$$ \begin{align} m_1\frac{d^2 x_1}{dt^2} = -K \Big(\frac{m_1 + m_2}{m_2}\Big)x1 \\ m_2\frac{d^2 x_2}{dt^2} = -K \Big(\frac{m_1 + m_2}{m_2}\Big)x2 \tag{14} \end{align} $$   

&nbsp; Multiply for each atom $$\Big(\frac{m_2}{m_1 + m_2} \Big) $$ and adding, we obtain :

$$\frac{m_1 m_2}{m_1 + m_2} \Big(\frac{d^2 x_1}{dt^2} + \frac{d^2 x_2}{dt^2}\Big) = -K(x_1 + x_2) \tag{15} $$

&nbsp; Introducing the reduced mass $$(\mu)$$ and the displacement $$(q = x_1 + x_2)$$, the Eq.15 is written as :

$$\mu \frac{d^2 q}{dt^2} = -Kq \tag{16} $$

&nbsp; Here, the solution of thie differential equation is 

$$q=q_0 sin(2\pi \nu_0 t + \varphi) \tag{17} $$

where $$q_0$$ is the maximum displacement and $$\varphi$$ is the phase constant.(depends on the inital conditions.) $$v_0$$ is the classical vibrational frequency given by 

$$\nu_0 = \frac{1}{2\pi} \sqrt{\frac{K}{\mu}} \tag{18} $$

&nbsp; We can calculate the potential energy $$(V) $$ and the kinetic energy $$(T)$$ as :

$$ \begin{align}
 dV &= -f\;dq = Kq\;dq \\
V &= \frac{1}{2}Kq^2  \\ 
&=\frac{1}{2} Kq^2_0 sin^2(2\pi \nu_0 t + \varphi) \\
&=2\pi^2 \nu_0^2 \mu q^2_0 sin^2(2\pi\nu_0 t + \varphi) \tag{19}\\ \\ 
T &= \frac{1}{2} m_1 \Big(\frac{dx_1}{dt}\Big)^2 + \frac{1}{2} m_2 \Big(\frac{dx_2}{dt} \Big)^2 \\
&= \frac{1}{2}\mu \Big(\frac{dq}{dt}\Big)^2 \\
&= 2\pi^2 \nu^2_0 \mu q_0^2 cos^2(2\pi \nu_0 t + \varphi) 
 \tag{20} 
 \end{align} $$

 &nbsp; Thus, the total energy $$(E)$$ is :

 $$ \begin{align}
 E &= T + V \\
&=2\pi^2\nu^2_0q_0^2 \quad (\because sin^2 x + cos^2 x  = 1) \\
&= constant
\tag{21} 
\end{align} $$





[TOP](#){: .btn .btn--primary }{: .align-right}

<!-- 수식넣기
$$
\begin{align}
\mbox{Union: } & A\cup B = {x\mid x\in A \mbox{ or } x\in B} \tag{1}\\
\mbox{Concatenation: } & A\circ B = {xy\mid x\in A \mbox{ and } y\in B} \tag{2}\\
\mbox{Star: } & A^\star = {x_1x_2\ldots x_k \mid k\geq 0 \mbox{ and each } x_i\in A} \tag{3}
\end{align}
$$
-->