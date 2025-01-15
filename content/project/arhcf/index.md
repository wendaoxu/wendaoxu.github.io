---
title: Brillouin in AR-HCF
date: 2018-10-01
#external_link: https://github.com/pandas-dev/pandas
tags:
  - Brillouin
  - Specialty optical fiber
---

Weak forward intra-modal Brillouin scattering in anti-resonant hollow-core fibers.

<!--more-->

<p>This project targeted at characterizing forward intra-modal Brillouin scattering in an anti-resonant hollow-core fiber. </p>
<p>I numerically simulated the guided optical and acoustic modes to acquire their field distributions on the fiber cross-section, with a commercial finite-element solver, COMSOL Multiphysics. With the field distributions, I calculated the Brillouin gain coefficient that describves the coupling efficiency among the optical and acoustic waves traveling inside the fiber waveguide. Since the optical energy is concentrated inside the air of the hollow-core fiber, which has pretty weak Brillouin response as a gas material, the Brillouin gain coefficients correposnding to all the guided acoustic modes are small, at least two orders of magnitudes smaller than those in standard solid-core optical fibers.</p>
<p>I used an sensitive experimental setup to measure the weak Brillouin signal from the fiber. The setup consists of: Optical - tunable lasers, beam splitters, collimating lenses, optical filters. Mechanical - multi-axis translation stages. Electro-optical: intensity modulator, photodetectors. I adjusted the translation stages to efficiently couple light into and out of the fiber. I adjusted the output frequency of the electrical signal generator used on the intensity modulator, and track the corresponding Brillouin response from the system on a electrical spectrum analyzer. </p>
