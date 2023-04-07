---
layout: page
title: Research
---
I am doing my post-doc within the ASTRAL project, financed by the joint ASTRID program of ANR and AID. Among the objectives of
the project are the exploration of network architectures suitable for multi-dimensional complex SAR data (inteferometric, polarimetric and tomographic data) and the estimation of uncertainties associated to the network prediction.


The subject of my Ph.D was: "Deep Learning for SAR imagery: from denoising to scene understanding". Throughout
my Ph.D thesis, I have explored supervised, semi-supervised and unsupervised deep learning approaches for speckle reduction from Synthetic Aperture Radar images. The fluctuations
caused by speckle seriously limit the exploitation of SAR data. The speckle phenomenon has a deterministic yet unpredictable phenomenon: it is often modeled as a random variable and
treated as a multiplicative noise. At first, we proposed to create a dataset of groundtruth images to train a deep model for speckle reduction, namely <a href="https://gitlab.telecom-paris.fr/ring/SAR-CNN">SAR-CNN</a>.
To account for specific acquisition modality, introducing speckle spatial correlation, we then introduce a semi-supervised approach to train neural networks directly on SAR data:<a href="https://gitlab.telecom-paris.fr/ring/SAR2SAR">SAR2SAR</a>.
The algorithm relies on the noise2noise framework and on SAR time-series. However, one does not always have access to more images acquired over a same area. With <a href="https://gitlab.telecom-paris.fr/ring/MERLIN">MERLIN</a> we show
that, somehow counterintuitively, one can exploit the phase of a single-look complex SAR image to produce two independent subimages, namely the real and the imaginary part, creating ideal conditions to
perform unsupervised learning on single SAR images.
