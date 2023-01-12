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

$$ E = E_0cos2\pi vt \tag{1} $$

$$E_0$$ is the amplitude, $$v$$ is the frequency of radiation.

<br>
&nbsp; The distance between two points of the same phase in successive waves is called the _"wavelength"_ , $$\lambda$$, which us measured in units.($$\mathring{A}$$(angstrom), $$nm$$(nanometer), $$m\mu$$(millimicron), and $$cm$$(centimeter)). The relationships between them are:

$$1 \mathring{A} = 10^{-8} cm = 10^{-1} nm = 10^{-1} m\mu  \tag{2} $$

## Frequency

&nbsp; The frequency, $$v$$ is the number of waves in the distance light travels in one second. Thus, 

$$ v = \frac{c}{\lambda} \tag{3} $$

$$c$$ is the velocity of light $$(3 \times 10^{10} cm/s) $$. And if $$ \lambda $$ is in the unit of centimeters, its dimension is $$ (cm/s)/(cm) = 1/s $$. This "reciporal second" unit is also called the "hertz" $$(Hz)$$.
&nbsp; There's another parameter is the _"wavenumber"_, $$\tilde{v}$$ defined by

$$ \tilde{v} = \frac{v}{c} \tag{4} $$

&nbsp; The difference between $$v$$ and $$ \tilde{v} $$ is obvious. It has the dimension of $$ (1/s)/(cm/s) = 1/cm.$$ By combining Eq.(3),Eq.(4) we have

$$ \tilde{v} = \frac{v}{c} = \frac{1}{\lambda}(cm^{-1}) \tag{5} $$

&nbsp; Also, we can express by $$v$$

$$ v = \frac{c}{\lambda} = c \tilde{v} \tag{6} $$

&nbsp; As shown earlier, the wavenumber$$(\tilde{v})$$ and frequency $$(v)$$ are different parameters, yet these two terms are often used interchangeably. Thus, we can express by **IR** and **Raman spectrosopists** such as "frequency shift of $$10cm^{-1}$$". 
## Interacts with an electromagetic field
&nbsp; We can know a transfer energy from the field to the molecule and it can occur only when Bohr's frequency condition is satisfied.(If a molecule interacts with an electromagetic field). 

$$ \Delta E = hv = h\frac{c}{\lambda} = hc\tilde{v} \tag{7} $$

&nbsp; Here $$h$$ is Planck's constant $$(6.62 \times 10^{-27}erg\; s)$$ and $$ \Delta E $$ is the difference in energy between two quantized states. Thus, $$ \tilde{v} $$ is directly proportional to the energy of transition. 

&nbsp; Let's Suppose that

$$ \Delta E = E_2 - E_1 \tag{8} $$

$$ E_2 $$ : Energy of the exicted states, $$ E_1$$ : Energy of the gound states.

&nbsp; Then, the molecule _absorbs_ $$ \Delta E $$ when it is exited from $$ E_1 $$ to $$ E_2$$ ( $$E_1 \rightarrow E_2 $$ ) and _emits_ $$ \Delta E $$  when it reverts from $$ E_2 $$ to $$ E_1 $$ ( $$ E_2 \rightarrow E_1 $$ ).

&nbsp; We can express $$ \Delta E $$ in terms of various energy units. Thus, $$ 1 cm^{-1} $$ is :

$$ \begin{align} \Delta E &= E^2 - E^1 = hc\tilde{v} \\ &=[6.62 \times 10^{-27} (erg \; s)][3 \times 10^{10} (cm/s)][1(1/cm)] \\&= 1.99 \times 10^{-16} &\; (erg/molecule) \\ &= 1.99 \times 10^{-23} &\; (joule/molecule)\\ &= 2.86 &\; (cal/mole) \\ &=1.24 \times 10^{-4} &\; (eV/molecule) \end{align} $$

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