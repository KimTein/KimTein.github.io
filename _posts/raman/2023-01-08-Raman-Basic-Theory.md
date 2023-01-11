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

&nbsp; The frequency, $$v$$ is the number of waves in the distance light travels in one second. Thus, 

$$ v = \frac{c}{\lambda} \tag{3} $$

$$c$$ is the velocity of light $$(3 \times 10^{10} cm/s) $$. And if $$ \lambda $$ is in the unit of centimeters, its dimension is $$ (cm/s)/(cm) = 1/s $$. This "reciporal second" unit is also called the "hertz" $$(Hz)$$.
&nbsp; There's another parameter is the _"wavenumber"_, $$\tilde{v}$$ defined by

$$ \tilde{v} = \frac{v}{c} \tag{4} $$

&nbsp; The difference between $$v$$ and $$ \tilde{v} $$ is obvious. It has the dimension of $$ (1/s)/(cm/s) = 1/cm.$$ By combining formula (3),(4) we have

$$ \tilde{v} = \frac{v}{c} = \frac{1}{\lambda}(cm^{-1}) \tag{5} $$

Also, we can express by $$v$$

$$ v = \frac{c}{\lambda} = c \tilde{v} \tag{6} $$

&nbsp; As shown earlier, the wavenumber$$(\tilde{v})$$ and frequency $$(v)$$ are different parameters, yet these two terms are often used interchangeably. Thus, we can express by **IR** and **Raman spectrosopists** such as "frequency shift of $$10cm^{-1}$$". 
<br>
&nbsp; We can know a transfer energy from the field to the molecule and it can occur only when Bohr's frequency condition is satisfied.(If a molecule interacts with an electromagetic field). 

$$ \Delta E = hv = h\frac{c}{\lambda} = hc\tilde{v} \tag{7} $$

Here $$h$$ is Planck's constant $$(6.62 times 10^{-27}erg s)$$ and $$ \Delta E $$ is the difference in energy between two quantized states. Thus, $$ \tilde{v} $$ is directly proportional to the energy of transition. 

&nbsp; Let's Suppose that

$$ \Delta E = 


___
[맨 위로 이동하기](#){: .btn .btn--primary }{: .align-right}

<!-- 수식넣기
$$
\begin{align}
\mbox{Union: } & A\cup B = {x\mid x\in A \mbox{ or } x\in B} \tag{1}\\
\mbox{Concatenation: } & A\circ B = {xy\mid x\in A \mbox{ and } y\in B} \tag{2}\\
\mbox{Star: } & A^\star = {x_1x_2\ldots x_k \mid k\geq 0 \mbox{ and each } x_i\in A} \tag{3}
\end{align}
$$
-->