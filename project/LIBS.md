---
layout: page
title: Variable Selection in LIBS
excerpt: "Recent Projects"
---

Variable selection in LIBS

Laser-Induced Breakdown Spectroscopy (LIBS) is an emerging technique for the analysis of rocks and mineral samples. Artificial Neural Networks (ANN) have been used to estimate the concentration of minerals in samples from the LIBS spectra. These spectra are very high dimensional data, and it is known that only specific wavelengths have information of atomic and molecular features of the sample under investigation. In this work, a systematic method for selecting the wavelengths of LIBS spectra as well as the ANN model complexity, combining prior knowledge and variable selection algorithms is proposed. Several variable selection algorithms are compared for this purpose, namely KBest, a LASSO regularization and Principal Component Analysis. As illustrative example the estimation of copper concentration in pelletized mineral samples is analyzed. A dataset of LIBS emission spectra with 12287 wavelengths in the range of 185-1049 nm obtained from 131 samples of copper concentrates is used for regression analysis. An ANN is then trained considering the selected reduced wavelength data. The results are satisfactory using any of the variable selection algorithms along with prior knowledge, showing that the proposed method for selecting wavelengths outperforms the expert selection for LIBS data in terms of the Akaike Information Criterion (AIC).

Further details can be found at [this github repository](https://github.com/dannylc/LIBS-VARIABLE-SELECTION)
