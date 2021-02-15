---
layout: page
title: Variable Selection in LIBS
excerpt: "Recent Projects"
---

Variable selection in LIBS

Laser-induced breakdown spectroscopy (LIBS) is an emerging technique for the analysis of rocks and
mineral samples. Artificial neural networks (ANN) have been used to estimate the concentration
of minerals in samples from the LIBS spectra. These spectra are very high dimensional data, and
it is known that only specific wavelengths have information on atomic and molecular features of
the sample under investigation. This work presents a systematic methodology based on the Akaike
information criterion (AIC) for selecting the wavelengths of LIBS spectra as well as the ANN model
complexity, by combining prior knowledge and variable selection algorithms. Several variable selection
algorithms are compared within the proposed methodology, namely KBest, a least absolute shrinkage
and selection operator (LASSO) regularization, principal component analysis (PCA), and competitive
adaptive reweighted sampling (CARS). As an illustrative example, the estimation of copper, iron
and arsenic concentrations in pelletized mineral samples is performed. A dataset of LIBS emission
spectra with 12287 wavelengths in the range of 185-1049 nm obtained from 131 samples of copper
concentrates is used for regression analysis. An ANN is then trained considering the selected reduced
wavelength data. The results are satisfactory using LASSO and CARS algorithms along with prior
knowledge, showing that the proposed methodology is very effective for selecting wavelengths and
model complexity in quantitative analyses based on ANN and LIBS.

Further details can be found at [this github repository](https://github.com/dannylc/LIBS-VARIABLE-SELECTION)
