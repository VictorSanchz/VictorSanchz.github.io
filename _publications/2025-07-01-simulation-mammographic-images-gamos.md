---
title: "Simulation of digital mammographic images using GAMOS: Proof of concept"
collection: publications
permalink: /publication/2025-07-01-simulation-mammographic-images-gamos
date: 2025-07-01
venue: 'Physica Medica'
volume: '135'
pages: '104995'
citation: 'Lozano, F.R., Sanchez-Lara, V., Huerga, C., Martinez-Gomez, Luis C., & Garcia-Pinto, D. (2025). Simulation of digital mammographic images using GAMOS: Proof of concept. <i>Physica Medica</i>, 135, 104995.'
doi: '10.1016/j.ejmp.2025.104995'
paperurl: 'http://dx.doi.org/10.1016/j.ejmp.2025.104995'
---

### Abstract
**Purpose**:
To present a simulation pipeline for digital mammography based on the GAMOS framework, enabling realistic image formation and dose estimation using high-fidelity anatomical phantoms and flexible detector modeling.
**Methods**:
A complete in silico model was implemented using GAMOS and GEANT4, including a Siemens Mammomat Inspiration system geometry, VICTRE voxelized breast phantoms, and two detector models: a direct conversion detector (MCD) and a virtual detector (VD). The simulation incorporated an anti-scatter grid, dose scoring tools, and a GUI for parameter adjustment. Performance metrics were calculated according to IEC 62220-1-2:2007.
**Results**:
The simulation yielded realistic mammographic images and accurate dose estimates. The MTF, NNPS, and DQE were calculated for both detector models and compared against published values. Maximum DQE differences were approximately 20%, with comparisons performed at spatial frequencies of 0.5, 2.0 and 5.0 mm−1. The MTF
 was 4.25 mm−1 (VD) and 4.35 mm−1 (MCD). Anatomical noise analysis showed 
 values between 2.67 and 3.16, consistent with clinical data. Dose validation against AAPM TG-195 showed differences below 1.08%.
**Conclusion**:
The proposed simulation framework is capable of producing realistic mammographic images and accurate dose calculations using an accessible interface. This tool is suitable for virtual clinical trials and system performance evaluation, and allows further extension to advanced imaging techniques such as contrast-enhanced or phase-contrast mammography. Code: https://github.com/PREDICO-Project/MIMAC

[Access full paper here](http://dx.doi.org/10.1016/j.ejmp.2025.104995)
