---
title:      Natural Unit
date:       2017-06-27
cowsay:     /cowphy/assets/natural-unit-hbar-c/catsay-natural-unit-hbar-c.png
summary:    It's not natural at all.
tags: [natural unit, units]
---



At least it's natural to me. This relation

$$
1 = \hbar\cdot c = 197 \mathrm{MeV\cdot fm}
$$

is extremely useful for physicists.

In most of my works, we would like to convert everything into energy scale or length scale for easy understanding. 

The cat says, he need to estimate the neutrino oscillation scales. The only know energy scales are mass squared difference $\delta m^2$ and neutrino energy $E$. It turns out that the only energy scale in equation of motion is $\delta m^2/2E \sim 10^{-5}\mathrm{eV^2}/2E$. [^1] Since this is the only energy scale and vacuum neutrino oscillation is a linear phenomenon, the oscillation scale should be inversely proportional to it,

$$
\begin{align}
L^{-1} &\sim 10^{-5} \mathrm{eV^2}/E \sim 10^{-17} \mathrm{MeV^2}/E\\
&\sim 10^{-17} \frac{\mathrm{MeV^2} }{1 \mathrm{MeV} } \frac{1 \mathrm{MeV} }{E} \\
&\sim 10^{-17} \mathrm{MeV}  \frac{1 \mathrm{MeV} }{E} \\
&\sim 10^{-17} \frac{1}{197\mathrm{fm}} \frac{1 \mathrm{MeV}}{E} \\
&\sim 10^{-1} \mathrm{km^{-1}} \frac{1 \mathrm{MeV}}{E}
\end{align}.
$$

We conclude that 
$$
L \sim 10 \mathrm{km} \left(\frac{E}{1 \mathrm{MeV}}\right).
$$
For 1MeV neutrinos, the oscillation scale is 10km. Higher energy neutrinos will oscillate with larger wavelength.




[^1]: We have chosen the mass squared difference to be $\delta m^2_{12}$.