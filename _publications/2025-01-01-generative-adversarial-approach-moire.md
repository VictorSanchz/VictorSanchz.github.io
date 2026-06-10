---
title: "A Generative Adversarial Approach to Remove Moiré Artifacts in Dark-Field and Phase-Contrast X-Ray Images"
collection: publications
permalink: /publication/2025-01-01-generative-adversarial-approach-moire
date: 2025-01-01
venue: 'Lecture Notes in Computer Science (LNCS)'
volume: '15451 LNCS'
pages: '181-190'
citation: 'García, E., del Ángel, R.M., Martí, R., García-Pinto, D., & Sánchez-Lara, V. (2025). A Generative Adversarial Approach to Remove Moiré Artifacts in Dark-Field and Phase-Contrast X-Ray Images. <i>Lecture Notes in Computer Science</i>, 15451, 181-190.'
---

### Abstract
X-ray phase contrast is a promising breast image modal
ity. This technique is capable of simultaneously providing three types 
of images: absorption, differential phase contrast (DPC) and dark-field 
(DF) images, allowing to obtain complementary information from each 
one. However, the Talbot-Lau interferometer, the device used to acquire 
this type of images, can yield Moiré artifacts in the corresponding images. 
The aim of this work is to introduce a deep learning approach, using a 
generative adversarial network, in particular the pix2pix neural network, 
to reduce Moiré artifacts efficiently. Our approach was tested using sim
ulated DPC and DF images obtained from the INbreast dataset. Moiré 
and mammography-based images are fused using a novel approach which 
aims to eliminate the bias yielded by the traditional one. Results shows 
a significant image quality improvement for the DF dataset, reaching a 
structural similarity (SSIM) index of .SSIM =0.96 ± 0.02, in average, 
after applying the neural network. However, under the same training con
ditions, the denoised DPC images do not show such a clear improvement, 
yielding checkerboard and discontinuity artifacts. 
