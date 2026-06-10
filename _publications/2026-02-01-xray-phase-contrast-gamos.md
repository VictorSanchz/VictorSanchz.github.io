---
title: "X-ray phase contrast imaging in GAMOS"
collection: publications
permalink: /publication/2026-02-01-xray-phase-contrast-gamos
date: 2026-02-01
venue: 'Physica Medica'
volume: '142'
pages: '105716'
citation: 'Sanchez-Lara, V., Lozano, F.R., Huerga, C., Martinez-Gomez, Luis C., & Garcia-Pinto, D. (2026). X-ray phase contrast imaging in GAMOS. <i>Physica Medica</i>, 142, 105716.'
doi: '10.1016/j.ejmp.2026.105716'
paperurl: 'http://dx.doi.org/10.1016/j.ejmp.2026.105716'
---

### Abstract
**Objective**:
X-ray Phase Contrast Imaging (PCI) enhances image contrast for weakly attenuating materials and has become increasingly relevant in biomedical and material science applications. The aim of this work is to develop and verify a Monte Carlo framework capable of realistically simulating PCI phenomena, including both refraction and wavefront propagation.
**Methods**:
We have developed and integrated two complementary simulation modules within the GAMOS (GEANT4-based Architecture for Medicine-Oriented Simulations) framework. The first models refraction effects using the X-ray complex refractive index and Snell’s Law. The second constructs the complex wavefront from the simulated photons and propagates it using the Fresnel formalism. Verification was carried out by simulating interferometric setups such as Young’s double-slit experiment and the Talbot effect, as well as full imaging configurations for PBI and Grating-Based Imaging (GBI).
**Results**:
The Snell-based simulation accurately reproduces edge-enhancement features typical of high-Fresnel-number PBI. However, in regimes where diffraction and interference dominate, the wave model yields significantly more accurate results. The agreement with theoretical predictions in all tests confirms the correct implementation of wavefront construction and propagation.
**Conclusions**:
This new simulation environment extends the MIMAC platform previously developed by our group and enables realistic Monte Carlo simulations of PCI. The framework is well-suited for optimizing imaging system design, developing reconstruction algorithms, or generating synthetic datasets for Deep Learning. The combination of geometrical and wave-optical models allows flexible simulation of a wide range of PCI setups under realistic physical conditions.
**Code**: https://github.com/PREDICO-Project/PCI-GAMOS

[Access full paper here](http://dx.doi.org/10.1016/j.ejmp.2026.105716)
