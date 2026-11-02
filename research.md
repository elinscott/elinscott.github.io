---
layout: default 
title: Research
---

{% include figure-gallery.html figures=site.data.research_figures %}

### Koopmans functionals
Density functional theory (DFT) gets band gaps and photoemission spectra badly wrong because its orbital energies do not match the true energies for adding or removing an electron. Koopmans functionals fix this by imposing a generalised piecewise-linearity condition on every orbital, giving spectral properties with accuracy comparable to GW at a fraction of the cost. I lead the development of the open-source [`koopmans`](https://koopmans-functionals.org) code, and work on extending these functionals, making them faster, and applying them to materials such as photocatalysts and perovskites.

### Hubbard corrections and exact conditions
DFT+_U_ is a cheap and widely used correction for materials with localised _d_ or _f_ electrons, but its results hinge on its parameters and its form was borrowed from the Hubbard model rather than derived from first principles. I work on computing these parameters from first principles, on understanding extensions such as DFT+_U_+_V_, and on deriving exact conditions of DFT that can guide the design of new corrections.

See [papers](./papers.html) to find out more.
