---
layout: single
title: The MaCoMaOc project
header:
  image: /assets/images/MaCoMaOc_Banner.png
  image_description: "Convection mode with phase change at both boundaries"

permalink: /MaCoMaOc/
---

The MaCoMaOc project is joint between the
[Laboratoire de géologie de Lyon](http://lgltpe.ens-lyon.fr/) (ENS de Lyon, Université Claude Bernard-Lyon 1)
and the [Institute für Geophysik](http://www.geophysics.ethz.ch/) (Department of Earth Sciences, ETH Zürich)
and is devoted to the study of **mantle convection in planetary mantles interacting with magma oceans above and/or below**.

It is funded by the [ANR](http://www.agence-nationale-recherche.fr/) on the French side and the [SNF](http://www.snf.ch/) on the Swiss side.

# Scientific questions
Convection in the solid mantle of terrestrial planets and in the icy layers of some satellites of Jupiter and Saturn
is or was occuring while an ocean of similar composition exists above and/or below. The possibility of melting and freezing
at the horizontal boundaries of the solid layer modifies its dynamics: A vertical flow toward the boundary needs not necessarily
come to a halt since matter can flow through the boundary by melting. Conversely, matter can enter the domain by freezing
in regions of flow away from the boundary. For this to happen, a heat flow in the liquid layer is necessary to redistribute
latent heat from regions of freezing to regions of melting. We consider this effect on mantle convection and implied
evolution of planets through application of boundary conditions originally developed for the dynamics of Earth's inner core.

# Contributors
In Lyon:
* Stéphane Labrosse (PI)
* [Renaud Deguen](https://scholar.google.com/citations?user=qGu2Ak4AAAAJ&hl=fr)
* [Thierry Alboussière](http://perso.ens-lyon.fr/thierry.alboussiere)
* [Adrien Morison](http://adrienmorison.com/) (PhD student)
* [Roberto Agrusta](https://scholar.google.com/citations?user=WM2LMxEAAAAJ&hl=it) (Post-doc)

In Zürich:
* [Paul Tackley](http://jupiter2.ethz.ch/~pjt/) (PI)
* [Daniela Bolrão](https://www.researchgate.net/profile/Daniela_Bolrao) (PhD student)
* [Maxim Ballmer](http://jupiter.ethz.ch/~ballmerm/)
* [Antoine Rozel](http://jupiter.ethz.ch/~arozel)

# Achievements
## Model development
* A pseudo-spectral Chebyshev collocation code has been written to solve the linear stability problem of convection with phase change boundary
conditions at either or both horizontal boundaries, in cartesian and spherical shell geometry. The weakly non-linear analysis is also implemented
for the 2D cartesian geometry. Results for the cartesian geometry are
presented in a paper published in the *Journal of Fluid Mechanics*
(Labrosse et al, 2018).
A paper has been accepted for publication in *Earth and Planetary
Science Letters* (Morison et al, 2019) in which we present linear
stability calculations for the timescale of the mantle overturn during
its crystallisation in a magma ocean. 
Another publication about the linear stability and non-linear
numerical simulation in spherical shells is in preparation (lead
author: Adrien Morison).
Direct numerical simulations of convection in a plane layer have also
been performed and a publication is being prepared (lead author:
Roberto Agrusta).
* In this project, we use the code StagYY (Tackley 2008) as main tool to model mantle convection. This requires some modifications:
  - we implemented the phase change boundary conditions.
  - we implemented the variation of composition by fractional crystallisation at regions of ingoing flow and treatment of compositional aspects
  in the solid using tracers.
  - we implemented the moving boundaries owing to the net motion
  during secular evolution.
* Aside from the main frame but still part of this project, we
  published a paper on the evolution of an initially stably stratified
  basal magma ocean (Laneuville et al, 2018).

## Publications
{% include MaCoMaOc.html %}

## Presentations in conferences and workshops
{% include conf_MaCoMaOc.html %}


