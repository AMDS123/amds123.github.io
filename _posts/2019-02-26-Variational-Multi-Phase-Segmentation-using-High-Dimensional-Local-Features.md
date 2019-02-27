---
layout: post
title: "Variational Multi-Phase Segmentation using High-Dimensional Local Features"
date: 2019-02-26 11:19:20
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation
author: Niklas Mevenkamp, Benjamin Berkels
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for multi-phase segmentation of images based on high-dimensional local feature vectors. While the method was developed for the segmentation of extremely noisy crystal images based on localized Fourier transforms, the resulting framework is not tied to specific feature descriptors. For instance, using local spectral histograms as features, it allows for robust texture segmentation. The segmentation itself is based on the multi-phase Mumford-Shah model. Initializing the high-dimensional mean features directly is computationally too demanding and ill-posed in practice. This is resolved by projecting the features onto a low-dimensional space using principle component analysis. The resulting objective functional is minimized using a convexification and the Chambolle-Pock algorithm. Numerical results are presented, illustrating that the algorithm is very competitive in texture segmentation with state-of-the-art performance on the Prague benchmark and provides new possibilities in crystal segmentation, being robust to extreme noise and requiring no prior knowledge of the crystal structure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09863](http://arxiv.org/abs/1902.09863)

##### PDF
[http://arxiv.org/pdf/1902.09863](http://arxiv.org/pdf/1902.09863)

