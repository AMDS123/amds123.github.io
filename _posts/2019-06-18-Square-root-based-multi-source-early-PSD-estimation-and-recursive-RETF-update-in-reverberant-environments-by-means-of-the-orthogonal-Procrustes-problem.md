---
layout: post
title: "Square root-based multi-source early PSD estimation and recursive RETF update in reverberant environments by means of the orthogonal Procrustes problem"
date: 2019-06-18 11:02:29
categories: arXiv_SD
tags: arXiv_SD OCR Relation
author: T. Dietzen, S. Doclo, M. Moonen, T. van Waterschoot
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-channel short-time Fourier transform (STFT) domain-based processing of reverberant microphone signals commonly relies on power-spectral-density (PSD) estimates of early source images, where early refers to reflections contained within the same STFT frame. State-of-the-art approaches to multi-source early PSD estimation, given an estimate of the associated relative early transfer functions (RETFs), conventionally minimize the approximation error defined with respect to the early correlation matrix, requiring non-negative inequality constraints on the PSDs. Instead, we here propose to factorize the early correlation matrix and minimize the approximation error defined with respect to the early-correlation-matrix square root. The proposed minimization problem -- constituting a generalization of the so-called orthogonal Procrustes problem -- seeks a unitary matrix and the square roots of the early PSDs up to an arbitrary complex argument, making non-negative inequality constraints redundant. A solution is obtained iteratively, requiring one singular value decomposition (SVD) per iteration. The estimated unitary matrix and early PSD square roots further allow to recursively update the RETF estimate, which is not inherently possible in the conventional approach. An estimate of the said early-correlation-matrix square root itself is obtained by means of the generalized eigenvalue decomposition (GEVD), where we further propose to restore non-stationarities by desmoothing the generalized eigenvalues in order to compensate for inevitable recursive averaging. Simulation results indicate fast convergence of the proposed multi-source early PSD estimation approach in only one iteration if initialized appropriately, and better performance as compared to the conventional approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07493](http://arxiv.org/abs/1906.07493)

##### PDF
[http://arxiv.org/pdf/1906.07493](http://arxiv.org/pdf/1906.07493)

