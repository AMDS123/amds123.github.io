---
layout: post
title: "DCASE 2019: CNN depth analysis with different channel inputs for Acoustic Scene Classification"
date: 2019-06-10 09:32:41
categories: arXiv_SD
tags: arXiv_SD CNN Classification Prediction Recognition
author: Javier Naranjo-Alcazar, Sergi Perez-Castanos, Pedro Zuccarello, Maximo Cobos
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of this technical report is to describe the framework used in Task 1, Acoustic scene classification (ASC), of the DCASE 2019 challenge. The presented approach is based on Log-Mel spectrogram representations and VGG-based Convolutional Neural Networks (CNNs). Three different CNNs, with very similar architectures, have been implemented. Themain difference is the number of filters in their convolutional blocks. Experiments show that the depth of the network is not the most relevant factor for improving the accuracy of the results.The performance seems to be more sensitive to the input audio representation. This conclusion is important for the implementation of real-time audio recognition and classification systemon edge devices. In the presented experiments the best audio representation is the Log-Mel spectrogram of the harmonic andpercussive sources plus the Log-Mel spectrogram of the difference between left and right stereo-channels. Also, in order to improve accuracy, ensemble methods combining different model predictions with different inputs are explored. Besides geometric and arithmetic means, ensembles aggregated with the Orness Weighted Averaged (OWA) operator have shown interesting andnovel results. The proposed framework outperforms the baseline system by 14.34 percentage points. For Task 1a, the obtained development accuracy is 76.84 percent, being 62.5 percent the baseline, whereas the accuracy obtained in public leaderboard is 77.33 percent,being 64.33 percent the baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04591](http://arxiv.org/abs/1906.04591)

##### PDF
[http://arxiv.org/pdf/1906.04591](http://arxiv.org/pdf/1906.04591)

