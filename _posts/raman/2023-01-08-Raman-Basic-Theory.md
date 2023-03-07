---
title           : "[Basic Theory.1] Basic Theory"
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

$$ \begin{align*}
 dV &= -f\;dq = Kq\;dq \\
V &= \frac{1}{2}Kq^2  \\ 
&=\frac{1}{2} Kq^2_0 sin^2(2\pi \nu_0 t + \varphi) \\
&=2\pi^2 \nu_0^2 \mu q^2_0 sin^2(2\pi\nu_0 t + \varphi) \tag{19}\\ \\ 
T &= \frac{1}{2} m_1 \Big(\frac{dx_1}{dt}\Big)^2 + \frac{1}{2} m_2 \Big(\frac{dx_2}{dt} \Big)^2 \\
&= \frac{1}{2}\mu \Big(\frac{dq}{dt}\Big)^2 \\
&= 2\pi^2 \nu^2_0 \mu q_0^2 cos^2(2\pi \nu_0 t + \varphi) 
 \tag{20} 
 \end{align*} $$

 &nbsp; Thus, the total energy $$(E)$$ is :

 $$ \begin{align*}
 E &= T + V \\
&=2\pi^2\nu^2_0q_0^2 \quad (\because sin^2 x + cos^2 x  = 1) \\
&= constant
\tag{21} 
\end{align*} $$

<br>

<center>
<img alt="Potentail energy diagram" src="/assets/images/posts/raman/Potential energy diagram.png" width = 500>
</center>
___
<figcaption style="text-align: center;">
[Figure. 5] Potential energy diagram for a harmonic oscillator. </figcaption>
<br>

&nbsp; [Figure. 5] is based on the book. It shows the plot of $$V$$ as a function of $$q$$ and looks like a vibrator called a _harmonic oscillator._

## Quantum Mechanics

&nbsp; Considering a motion of a single particle having mass $$\mu$$, the vibration can be written for the Schrödinger equation as 

$$ \frac{d^2 \psi}{dq^2} + \frac{8 \pi^2 \mu }{h^2} \Big(E-\frac{1}{2}Kq^2 \Big)\psi = 0 \tag{22}$$

&nbsp; If the $$\psi$$ must be single-valued,finite and continuous, the eigenvalues are written as by solving the Eq.22 :

$$ E_v = h\nu \Big(v + \frac{1}{2} \Big) = hc\tilde{\nu} \Big( v + \frac{1}{2}\Big) \tag{23} $$

&nbsp; And the frequency of vibration is as follows seems like Eq.18

$$\nu = \frac{1}{2\pi} \sqrt{\frac{K}{\mu}} \tag{24} $$

where $$v$$ is the [vibrational quantum number][linkvqn], and having the values 0,1,2... So, the corresponding eigenfunctions are :

[linkvqn]: https://en.wikipedia.org/wiki/Molecular_vibration

$$ \psi _v = \frac{(\alpha / \pi)^{1/4}}{\sqrt{2^{\mathrm{v}} v!}}e^{-\alpha q^2 / 2} H_v(\sqrt{\alpha q}) \tag{25} $$

where $$ \alpha = 2\pi \sqrt{\mu K/h} = 4\pi^2 \mu v/h $$ and $$H_v(\sqrt{\alpha q}) $$ is a [Hermite polynomial][linkHermite] of the $\mathrm{v}^{th} $ degree.

[linkHermite]:https://en.wikipedia.org/wiki/Hermite_polynomials

&nbsp; Thus, the eigenvalues and the corresponding eigenfunctions are

$$ \begin{align*} 
&v = 0, \quad E_0 = \frac{1}{2} hv, \quad \psi _0 = (\alpha / \pi)^{1/4} e^{-\alpha q^2 /2} \\
&v = 1, \quad E_1 = \frac{3}{2} hv, \quad \psi _1 = (\alpha / \pi)^{1/4} 2^{1/2}qe^{-\alpha q^2 /2} \tag{26}
\end{align*} $$

$$ \vdots $$

### Difference of the frequency between classical & quantum-mechanical

&nbsp; The quantum mechanical frequency(Eq.24) is same as the classical frequency(Eq.18). However, there are some differences noted between the two treatments.

&nbsp; First, the zero-state Engergy. Classicaly, the energy _E_ is zero when _q_ is zero. 

$$ q=0 \rightarrow E=0 \tag{27-1} $$

But, in the Quantum-mechanically, the lowest _E_ state $$(v=0)$$ has the energy, $$\frac{1}{2} h\nu $$ (=zero point energy).
That's because the Heisenberg's uncertainly prinicple.

$$ v=0 \rightarrow E = \frac{1}{2} h\nu \quad (\because uncertainly principle) \tag{27-2} $$

&nbsp; Second, continuity of a vibrator. Classicaly, vibrator can change contiuosly. But In quantum mechanics, the energy, _E_ can change only in units of $$h\nu$$. 



|Vibrator|Continuity|
|:------:|:------:|
|Classical|continuous|
|Quantum|units of $h\nu$|

<br>

&nbsp; Thirdly, probability of breakaway from the parabola. Classically, the vibration is confined within the parabola. Because if $\vert q \vert > \vert q_0 \vert$, the _T_ becomes negative. Contrary, in quantum-mechanics, the probability (of finding _q_ outside the parabola) is not zero since the [_tunnel effect_][linktunnel].

[linktunnel]: https://en.wikipedia.org/wiki/Quantum_tunnelling

## Hot Band

<center>
<a href='https://en.wikipedia.org/wiki/Morse_potential'>
<img alt="Internuclear Distance" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Morse-potential.png/800px-Morse-potential.png" width = 500>
</a>
</center>
___
<figcaption style="text-align: center;">
[Figure. 6] Internuclear Distance </figcaption>
<br>

&nbsp; Hereafter, talk about the separation between the two vibrational levels. \\
In the case of a harmonic oscillator, that is always same with $h\nu$. But an actual molecule is not the case. The potential is approximated by the [Morse potential function][linkMorse] shown by the solid curve like [Figure. 6]. 

[linkMorse]: https://en.wikipedia.org/wiki/Morse_potential

$$ V = D_e(1-e^{-\beta q})^2 \tag{28} $$

where $D_e$ is the dissociation energy, $\beta$ is a measure of the curvature an the bottom of the potentail well.\\
The eigenvalues by solving with the Schrödinger equation :

$$ E_v = hcw_e \Big(v + \frac{1}{2} \Big) - hc\chi_e w_e \Big(v+\frac{1}{2} \Big )^2 + \cdots \tag{29} $$

where $w_e$ is the wavenumber corrected for anharmonicity, $\chi_e w_e$ indicates the magnitude of anharmonicity.\\
&nbsp; By Eq.29, the _E_ levels of the anharmonic oscillator are no longer equidistant. And the separtion decreases with increasing $\nu$ like [Figure. 6].\\
&nbsp; According to quantum-mechanics, Only in a harmonic oscillator, those transitions involving $\Delta v = \pm 1 $ are allowed. Else, the transitions involving $\Delta v = \pm 2, \pm 3, \dots$ (overtones). Both in **IR** and **Raman spectra**, many $\Delta v = \pm 1 $ transitions that of $v = 0 \leftrightarrow 1 $ appears most strongly. That is expected from the [Maxwell-Boltzmann distribution law][linkMaxwell], which states that the population ration of the $v=1 $ and $v = 0$ states is given by 

[linkMaxwell]:https://en.wikipedia.org/wiki/Maxwell–Boltzmann_distribution

$$\frac{P_{v=1}}{P_{v=0}} = e^{-\Delta E/kT} \tag{30} $$

where $\Delta E$ is the energy difference between the two states, $k$ is Boltzmann's constant $(1.3807 \times 10^{-16} \; erg/degree)$, and $T$ is the absolute temperature.
Since $\Delta E = hc\tilde{v}$, the ratio is inversely proportional with $\tilde{v}$. $(\frac{P_{v=1}}{P_{v=0}} \propto \frac{1}{\tilde{v}}) $

&nbsp; Example, the $\tilde{v}$ of $\mathrm{H}_2$ is $4,160 \; cm^{-1}$, $T$ is room temperature $(300K)$


$$ 
  \begin{align*}
    kT &= 1.38 \times 10^{-6} \; (erg/degree) \quad 300 \; (degree) \\
    &= [4.14 \times 10^{-14} \; (erg)] / [1.99 \times 10^{-16} \; (erg)(cm^{-1})] \\
    &= 208 \; (cm^{-1}) \tag{31} \\
  \end{align*} 
$$

Then, the ratio is

$$ \frac{P_{v=1}}{P_{v=0}}=e^{-hc(4,160)/208} = 2.19 \times 10^{-9} \tag{32} $$

That means almost all of the molecules are at $v=0$.
<br>
&nbsp; If $\tilde{v} = 213 \; cm^{-1} $ ( $I_2$ molecule), the ratio is 0.36. That is abpit 27% of the $I_2$ molecules are at $v=1$ state. In this case, the transition $ v = 1 \rightarrow 2 $ should be observed on the low-frequency side of the fundamental with much less intensity. Such a transition is called a [**_"hot band"_**][linkhotband] since it tends to appear at higher temperatures.

[linkhotband]: https://en.wikipedia.org/wiki/Hot_band

# Origin of Raman Spectra

## IR absorption

&nbsp; Now measure the absorption of IR by the sample as a function of frequency. The molecule absorbs $\Delta E = hv$ from the IR source at each vibrational transition. The intensity of IR absorption is governed by the [**Beer-Lambert Law**][linkBeer] :

[linkBeer]: https://en.wikipedia.org/wiki/Beer–Lambert_law

$$ I = I_0 e^{-\varepsilon c d} \tag{33} $$

In IR spectroscopy, it's customary to plot the percentage transmission $(T)$ versus wave number $(\tilde{\nu})$:

$$ T(\%) = \frac{I}{I_0} \times 100 \tag{34} $$

Note : $T(\%)$ is not proportional to $c$. 
<br>
For quntitative analysis, the absorbance $(A)$ defined here should be used:

$$ A = log\frac{I_0}{I} = \varepsilon cd \tag{35} $$

## Raman spectra

<center>
<img alt="Differences in mechanism of Raman vs IR" src="/assets/images/posts/raman/RamanIR.jpeg" width = 500>
</center>
___
<figcaption style="text-align: center;">
[Figure. 7] Differences in mechanism of Raman vs IR (From book). </figcaption>
<br>

In [Figure. 7], Raman spectra is different from that of IR spectra. The scattered light from the sample is observed in the direction perpendicualr to the incident beam. That consists of two types : 

1. Rayleigh scattering : is strong and has the same frequency as the incident beam.
2. Raman scattering : is very weak ( $ ~ 10^{-5} $ of the incident beam) and has frequencies $ \nu_0 \pm \nu_m$

At the Raman scattering, $\nu_0 - \nu_m$ is Stokes, and $\nu_0 + \nu_m$ is anti-Stokes lines. Thus, we measure the vibrational frequncy $(\nu_m)$ as a shift from the incident beam frequncy $(\nu_0)$.
<br>
In classical theory, Raman scattering follows:

$$ E = E_0 cos 2\pi \nu_0 t \tag{36} $$

If a diatomic molecule is irradiated, an electric dipole moment _P_ is induced :

$$ P = \alpha E = \alpha E_0 cos 2\pi \nu_0 t \tag{37} $$

The $\alpha$ is a proportionally constant ( _polarizability_). Frequency of the vibrating molecule is $\nu_m$, $q_0$ is the vibrational amplitude, the nuclear displacement _q_:

$$ q = q_0 cos 2\pi \nu_m t \tag{38} $$

For a small amplitude of vibration, $\alpha$ is a linear function of _q_. Thus, we can write

$$ \alpha = \alpha_0 + \Big(\frac{\partial \alpha}{\partial q} \Big)_0 q_0 + \cdots \tag{39}$$

Combining Eq.37 & Eq.38, we obtain :

$$ 
\begin{align} \\
  P &= \alpha E_0 cos 2\pi \nu_0 t \\
    &= \alpha_0 e_0 cos 2\pi \nu_0 t + \Big(\frac{\partial \alpha}{\partial q}\Big)_0 q E_0 cos 2\pi \nu_0 t \\
    &= \alpha_0 E_0 cos 2\pi \nu_0 t + \Big(\frac{\partial \alpha}{\partial q}\Big)_0 q_0 E_0 cos2\pi \nu_0 t cos 2\pi \nu_m t \\
    &= \alpha_0 E_0 cos 2\pi \nu_0 t + \frac{1}{2} \Big(\frac{\partial \alpha}{\partial q})_0 q_0 E_0 [cos {2\pi(\nu_0 + \nu_m)t} + cos {2\pi (\nu_0 - \nu_m)t}] 
    \tag{39} \\
\end{align}
$$  








___
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