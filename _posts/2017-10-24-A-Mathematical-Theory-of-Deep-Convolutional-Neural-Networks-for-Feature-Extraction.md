---
layout: post
title: "A Mathematical Theory of Deep Convolutional Neural Networks for Feature Extraction"
date: 2017-10-24 06:44:21
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN Classification
author: Thomas Wiatowski, Helmut Bölcskei
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks have led to breakthrough results in numerous practical machine learning tasks such as classification of images in the ImageNet data set, control-policy-learning to play Atari games or the board game Go, and image captioning. Many of these applications first perform feature extraction and then feed the results thereof into a trainable classifier. The mathematical analysis of deep convolutional neural networks for feature extraction was initiated by Mallat, 2012. Specifically, Mallat considered so-called scattering networks based on a wavelet transform followed by the modulus non-linearity in each network layer, and proved translation invariance (asymptotically in the wavelet scale parameter) and deformation stability of the corresponding feature extractor. This paper complements Mallat's results by developing a theory that encompasses general convolutional transforms, or in more technical parlance, general semi-discrete frames (including Weyl-Heisenberg filters, curvelets, shearlets, ridgelets, wavelets, and learned filters), general Lipschitz-continuous non-linearities (e.g., rectified linear units, shifted logistic sigmoids, hyperbolic tangents, and modulus functions), and general Lipschitz-continuous pooling operators emulating, e.g., sub-sampling and averaging. In addition, all of these elements can be different in different network layers. For the resulting feature extractor we prove a translation invariance result of vertical nature in the sense of the features becoming progressively more translation-invariant with increasing network depth, and we establish deformation sensitivity bounds that apply to signal classes such as, e.g., band-limited functions, cartoon functions, and Lipschitz functions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1512.06293](https://arxiv.org/abs/1512.06293)

##### PDF
[https://arxiv.org/pdf/1512.06293](https://arxiv.org/pdf/1512.06293)

