# Classical image-processing MNIST classifier, Deblurring

## Overview
Implements a classical image-processing MNIST classification pipeline (no learned neural nets), provides proofs for autocorrelation properties, and implements deblurring/restoration algorithms (Wiener and frequency-domain).

## What I implemented
- **Classical MNIST classifier**
  - Preprocessing: normalization, centering and size normalization.
  - Feature extraction: FFT magnitude summaries, morphological descriptors, moment-based features and autocorrelation peaks.
  - Rule-based classifier combining interpretable features; evaluation includes accuracy, per-class accuracy and confusion matrix.
- **Mathematical proof**
  - Proof demonstrating autocorrelation properties and relevant inequalities (documented step-by-step).
- **Image restoration**
  - Wiener filter and frequency-domain deblurring for motion blur; PSF estimation discussion and example implementations.
- **Filtering & artifacts**
  - Identification and restoration of common artifacts; visual examples provided.

Please refer to the notebook for more information: src/main.ipynb